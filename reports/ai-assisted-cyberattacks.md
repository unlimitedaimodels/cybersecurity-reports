# AI-Assisted Cyberattacks

AI changes the speed and scale of familiar attacks. It can help attackers draft convincing messages, search code, automate reconnaissance, and adapt social engineering. Defensive programs should focus on observable behavior rather than guessing whether a human or model produced it.

## Defensive priorities

- Log tool calls, identity changes, and unusual automation patterns.
- Treat model output as untrusted input and validate generated code.
- Protect secrets in prompts, repositories, CI logs, and agent memory.
- Restrict agent permissions with short-lived credentials and explicit scopes.
- Test prompt injection and data exfiltration paths in authorized environments.

AI security is part of application security, identity security, and supply-chain security.

## Primary sources

- [CISA AI Security Guidance](https://www.cisa.gov/topics/artificial-intelligence)
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [Microsoft Digital Defense Report](https://www.microsoft.com/en-us/corporate-responsibility/topics/cybersecurity/reports/microsoft-digital-defense-report/)

See more [cybersecurity reports](../README.md) and [UnlimitedAI](https://unlimitedai.sh/).
