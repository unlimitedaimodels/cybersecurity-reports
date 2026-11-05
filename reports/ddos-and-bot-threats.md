# DDoS and Bot Threats

Availability attacks range from volumetric floods to low-volume automation that abuses login, search, checkout, or API endpoints. Defense should be layered and measured against normal traffic.

## Defensive controls

- Establish baseline traffic by route, region, identity, and device.
- Apply adaptive rate limits with clear retry behavior.
- Protect expensive operations and authentication endpoints.
- Use caching and queueing where they reduce origin load.
- Keep an incident runbook with provider escalation contacts.

## Primary sources

- [Cloudflare DDoS Threat Report](https://www.cloudflare.com/ddos/threat-report/)
- [CISA DDoS Guidance](https://www.cisa.gov/news-events/news/understanding-denial-service-attacks)
- [OWASP Automated Threats](https://owasp.org/www-project-automated-threats-to-web-applications/)

See [cybersecurity reports](../README.md) and [UnlimitedAI](https://unlimitedai.sh/).
