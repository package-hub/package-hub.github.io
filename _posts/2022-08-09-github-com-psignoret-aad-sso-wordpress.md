---
title: aad-sso-wordpress
categories: ['php', 'azure-active-directory', 'wordpress-plugin']
---
## [aad-sso-wordpress](https://github.com/psignoret/aad-sso-wordpress)

### Single Sign-on with Azure Active Directory (for WordPress)


A WordPress plugin that allows organizations to use their Azure Active Directory
user accounts to sign in to WordPress. Organizations with Office 365 already have
Azure Active Directory (Azure AD) and can use this plugin for all of their users.

- Azure AD group membership can be used to determine access and role.
- New users can be registered on-the-fly based on their Azure AD profile.
- Can always fall back to regular username and password login.

*This is a work in progress, please feel free to contact me for help. This plugin is provided as-is, with no guarantees or assurances.*

In the typical flow:

1. User attempts to log in to the blog (`wp-admin`). At the sign in page, they are given a link to sign in with their Azure Active Directory work or school account (e.g. an Office 365 account).
2. After signing in, the user is redirected back to the blog with an authorization code, which the plugin exchanges for a ID token, containing a minimal set of claims about the signed in user, and an access token, which can be used to query Azure AD for additional details about the user.
3. The plugin uses the claims in the ID token to attempt to find a WordPress user with an email address or login name that matches the Azure AD user.
4. If one is found, the user is authenticated in WordPress as that user account. If one is not found, the WordPress user will (optionally) be auto-provisioned on-the-fly.
5. (Optional) Membership to certain groups in Azure AD can be mapped to roles in WordPress, and group membership can be used to restrict access.
