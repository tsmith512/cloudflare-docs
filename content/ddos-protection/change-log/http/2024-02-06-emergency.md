---
title: 2024-02-06 - Emergency
pcx_content_type: changelog
weight: 27723
layout: wide
---

# 2024-02-06 - Emergency

{{<table-wrap>}}
<table style="width: 100%">
  <thead>
    <tr>
      <th>Rule ID</th>
      <th>Description</th>
      <th>Previous Action</th>
      <th>New Action</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>...1fc1e601</td>
      <td>HTTP requests with unusual HTTP headers or URI path (signature #31).</td>
      <td>block</td>
      <td>block</td>
      <td>Modify characteristics of the unusual HTTP headers or URI path.</td>
    </tr>
<tr>
      <td>...3a679c52</td>
      <td>Requests coming from known bad sources.</td>
      <td>N/A</td>
      <td>ddos_dynamic</td>
      <td></td>
    </tr>
<tr>
      <td>...3ad719cd</td>
      <td>HTTP requests from known botnet (signature #79).</td>
      <td>ddos_dynamic</td>
      <td>ddos_dynamic</td>
      <td>Expand the scope of the rule to match more attacks.</td>
    </tr>

  </tbody>
</table>
{{</table-wrap>}}