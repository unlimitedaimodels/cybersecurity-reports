# Exposed Credentials and Secrets

Secrets in source code, JavaScript bundles, CI logs, and public artifacts can become immediate access paths. Prevention requires engineering controls and rapid response.

## Safer process

1. Keep secrets in a managed vault, never in source or client code.
2. Scan commits, pull requests, artifacts, and build logs.
3. Revoke and rotate exposed keys immediately.
4. Scope credentials to the smallest required permissions.
5. Record incident evidence without copying live secrets into tickets.

A detected secret is an incident signal, not permission to access a third-party system.

## Primary sources

- [GitHub Secret Scanning](https://docs.github.com/code-security/secret-scanning/introduction/about-secret-scanning)
- [CISA Secure Software](https://www.cisa.gov/topics/cyber-threats-and-advisories/secure-software)
- [NIST SSDF](https://csrc.nist.gov/Projects/ssdf)

See [cybersecurity reports](../README.md) and [UnlimitedAI](https://unlimitedai.sh/).
