# S14 - Modern Authentication Explained to the Network Professional [BRKSEC-2144]

## Theoretical-Input

  - PPTX: BRKSEC-2144.pdf

## Notes

Modern Auth & SSO for Networkers

Introduction
1. History & AAA
- SCIM
- Bad-User-Experience not like "SSO"
- FederationServices - "Thanks2Microsoft"
2. Enter: Single Sign On
3. SAML
4. OAuth & OIDC
 - App2App - OAuth2.0 as a Sec Standard
5. WebAuthN & Passkeys
6. Gotcha’s
-> Change of Authorization (CoA) - (S106)
Allows RADIUS server to disconnect or force other change in the authorization status of a user/endpoint.
• Disconnect
• Port-bounce
• Re-Authenticate
• Apply ACL

7. ID Needs Shades in Future
 - AuthN, AuthZ, - Shared Signals - OK ? (S129)

 - TheFuture (S144)

## Links

 - Shibboleth Consortium: https://www.shibboleth.net/index/
 - OASIS: https://www.oasis-open.org
 - Beer Drinkers Guide to SAML: https://duo.com/blog/the-beer-drinkers-guide-to-saml
 - Fighting Cookie Theft: https://blog.chromium.org/2024/04/fighting-cookie-theft-using-device.html
 - A demo of Webauthn and Passkeys: https://webauthn.io