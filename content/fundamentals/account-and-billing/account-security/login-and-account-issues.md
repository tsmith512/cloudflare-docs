---
title: Login and account issues
pcx_content_type: troubleshooting
weight: 1
---

# Login and account issues

## Forgot your email?

### Enterprise plans

If you forget the email address associated with your account, contact your Customer Success Manager.

### Free, Pro, and Business plans

If you forget the email address associated with your application:

1. Go to the [Cloudflare dashboard](https://dash.cloudflare.com/login) and select **Forgot your email?**.
2. Enter your domain name.
3. Cloudflare will send an email to the email address associated with your domain name. If you do not receive an email within 20 minutes, check your spam folder. The message will be sent from `no-reply@cloudflare.com` or `noreply@notify.cloudflare.com`.

{{<Aside type="note">}}
This process does not affect your account or share your email address with anyone.
{{</Aside>}}

If you still cannot access the email address associated with your Cloudflare account, you may need to [move your domain to another account](/fundamentals/setup/manage-domains/move-domain/).

Cloudflare requires these steps to prevent account hijacking.

___

## Forgot your password?

If you forget your account password:

1. Go to the [Cloudflare dashboard](https://dash.cloudflare.com/login) and select **Forgot your password?**.
2. Enter your email address.
3. Cloudflare will send an email to your email address to reset your password. If you do not receive it within 20 minutes, check your spam folder. The message will be sent from `no-reply@cloudflare.com` or `noreply@notify.cloudflare.com`.
4. Select the password reset link in the email. This link will expire after two hours.

{{<Aside type="note">}}

Cloudflare recommends strong passwords. Minimum requirements are:
-   Password must be at least 8 characters.
-   Password must contain a digit.
-   Password must contain a special character.
{{</Aside>}}

___

## Email verification issues

Refer to [Verify email address](/fundamentals/setup/account-setup/verify-email-address/).

___

## Change your Cloudflare email address or password

Refer to [Change password or email address](/fundamentals/account-and-billing/account-billing/change-password-or-email/).

___

## Secure a compromised account

If you observe suspicious activity within your Cloudflare account, secure your account using [these steps](/fundamentals/account-and-billing/account-security/securing-a-compromised-account/).

___

## Sign-in options

You have several sign-in options for the [Cloudflare dashboard](https://dash.cloudflare.com/login):

-   **Email and password**: Enter your email address and password to log in.
-   **Single sign on (SSO)**: Enter your email address (so long as your admin has [configured SSO](/cloudflare-one/applications/configure-apps/dash-sso-apps/) as a sign in option).
-   **Sign in with Apple**:
    -   _Same Cloudflare account email as Apple ID_: You can either sign in with your email and password or sign in with Apple.
    -   _Different Cloudflare account email as Apple ID_: Will create a new Cloudflare account if you sign in with Apple. If you want to log into an existing account, [change your email address](/fundamentals/account-and-billing/account-security/login-and-account-issues/) to match the one used for your Apple ID.

{{<Aside type="note">}}
If you login to your Cloudflare user account with Single Sign-On (SSO), you will not be able to sign in with Apple.
{{</Aside>}}

___

## Related resources

-   [Move domains between Cloudflare accounts](/fundamentals/setup/manage-domains/move-domain/)
-   [Secure user access with two-factor authentication (2FA)](/fundamentals/account-and-billing/account-security/2fa/)
-   [Change your domain nameservers to Cloudflare](/dns/zone-setups/full-setup/setup)
-   [Manage API keys and tokens](/fundamentals/api/get-started/)