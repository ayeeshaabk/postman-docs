---
title: "Intro to SSO"
order: 131
updated: 2020-05-22
page_id: "intro_sso"
warning: false
contextual_links:
  - type: section
    name: "Additional Resources"
  - type: subtitle
    name: "Videos"
  - type: link
    name: "Postman 101 for Admins | Webinar"
    url: "https://youtu.be/d6pw-0Yy5fs"

---

> __[SSO is available on Postman Professional and Enterprise plans.](https://www.postman.com/pricing)__

## What is SSO?

Single sign-on (SSO) services make it easy to manage your team’s identity across all the SaaS products that you use.

SSO services permit a user to use one set of credentials (for example, a name or email address and password) to access multiple applications. The service authenticates the end user only once for all the applications the user has been given rights to and eliminates further prompts when the user switches applications during the same session.

An example of SSO is Google's sign-in implementation for products like Gmail, YouTube, and Google Drive. Any user that is logged in to one of Google's products is automatically logged in to their other products as well.

### What are the advantages of SSO?

* Removes the need for users to remember and manage multiple passwords.
* Simplifies users' experience by allowing them to sign in at one single access point and enjoy a seamless experience across multiple applications.
* Increases productivity by significantly reducing the password-related support emails.
* Reduces phishing and thereby making sure users aren't tricked into giving away sensitive information.

### Prerequisites for SSO with Postman

* Team’s Identity Provider (IdP) must support the SAML 2.0 standard.

### Identity Providers Supported

* [Okta](https://www.okta.com/)
* [OneLogin](https://www.onelogin.com/)
* [Duo](https://duo.com/)
* [Ping Identity](https://www.pingidentity.com/en.html)
* [AD FS](https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc755226(v=ws.11))
* [GSuite](https://workspace.google.com/products/admin/)
* [Custom SAML](/docs/administration/sso/admin-sso/)

### SSO setup for SAML 2.0 compliant IdPs

Most SAML 2.0 compliant identity providers require the same information about the service provider for setup (Postman is the service provider). These values are specific to a Postman team and are available after configuring SSO in the Edit Team Page.

Learn more about [setting up SSO](/docs/administration/sso/admin-sso/).

**Note:** While configuring your IdP, make sure the user’s email address is set in attribute statements.

**Note:** Postman’s form-based authentication mechanism and Google OAuth 2.0 remain enabled even if SSO is configured for a team.
