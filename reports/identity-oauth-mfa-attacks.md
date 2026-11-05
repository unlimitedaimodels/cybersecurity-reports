# Identity OAuth and MFA Attacks

Identity incidents often begin with a valid session, token, or consent grant. Defenders should protect the full lifecycle: enrollment, authentication, token issuance, refresh, recovery, and revocation.

## Review checklist

- Require phishing-resistant MFA for privileged and sensitive actions.
- Validate token issuer, audience, expiry, nonce, and redirect URI.
- Alert on impossible travel, new devices, unusual consent, and session reuse.
- Rotate refresh tokens and revoke sessions after risk events.
- Keep recovery flows as strong as primary authentication.

## Primary sources

- [OAuth 2.0 RFC 6749](https://www.rfc-editor.org/rfc/rfc6749)
- [OpenID Connect Core](https://openid.net/specs/openid-connect-core-1_0.html)
- [CISA Identity Guidance](https://www.cisa.gov/topics/identity-and-access-management)

Read the [cybersecurity reports index](../README.md) and visit [UnlimitedAI](https://unlimitedai.sh/).
