### Cloudflare Firewall Rules To Prevent DDOS Attacks

## Firewall Rules

Rule Name | File Name | Action | What For
---- | ---- | ---- | ----
General | [rules.ssl](./rules.ssl) | Manual ADD | Peformance, User Experience, DDOS Protection, Crawlers<br>
Countries | [common-country.rules](./common-country.rules) | Block | Only Allow Country's Who Wont Pass Much Malicous Traffic.<br>
ASN List | [bad-asn.rules](./bad-asn.rules) | Block | ASN List Of Most Known Proxyscraping Sites.<br>
Threat Score | [threatscore.rules](./threatscore.rules) | Block | Block Bad Threats Flagged By Cloudflare<br>
Request Method | [request-method.rules](./request-method.rules) | Block | Block POST & HEAD Request's Only Allow GET Request's Unless Needed.<br>
