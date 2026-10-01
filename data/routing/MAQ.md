# Routing security and IPv6 — MAQ

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **Macquarie Technology Operations Pty Limited** (ORG-MCT1-AP) — 8 ASNs; 16 IPv4 blocks; 2 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-MCT1-AP (retrieved 2026-10-01T01:35:53Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 8 | APNIC RDAP |
| IPv4 blocks registered | 16 | APNIC RDAP |
| IPv6 blocks registered | 2 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 158 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 11 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 34 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 13 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 129 / 1 / 39 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 8 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS17477 | AU | 112 | 8 | 104/0/16 | none | seen=45, filter_rate=8.823529 (28-day); series date 2026-09-29 | seen=62.433333, capable_pc=0.480513, preferred_pc=0.266951 (30-day); series date 2026-09-29 |
| AS18349 | AU | 1 | 0 | 0/0/1 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-07-20 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-07-20 |
| AS55455 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2020-11-23 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-10-15 |
| AS56183 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.5, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2016-03-03 |
| AS136043 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS137214 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2021-06-08 |
| AS140637 | AU | 45 | 3 | 25/1/22 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-08-05 | seen=2.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-08-05 |
| AS141230 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |

## Source queries

- AS17477: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS17477 (2026-10-01T01:35:56Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU17477 (2026-10-01T01:35:59Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU17477 (2026-10-01T01:36:01Z)
- AS18349: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS18349 (2026-10-01T01:36:03Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU18349 (2026-10-01T01:36:06Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU18349 (2026-10-01T01:36:07Z)
- AS55455: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS55455 (2026-10-01T01:36:09Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU55455 (2026-10-01T01:36:12Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU55455 (2026-10-01T01:36:13Z)
- AS56183: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS56183 (2026-10-01T01:36:16Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU56183 (2026-10-01T01:36:19Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU56183 (2026-10-01T01:36:20Z)
- AS136043: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS136043 (2026-10-01T01:36:22Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU136043 (2026-10-01T01:36:25Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU136043 (2026-10-01T01:36:26Z)
- AS137214: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS137214 (2026-10-01T01:36:28Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU137214 (2026-10-01T01:36:31Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU137214 (2026-10-01T01:36:32Z)
- AS140637: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS140637 (2026-10-01T01:36:34Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU140637 (2026-10-01T01:36:37Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU140637 (2026-10-01T01:36:38Z)
- AS141230: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS141230 (2026-10-01T01:36:40Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU141230 (2026-10-01T01:36:42Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU141230 (2026-10-01T01:36:44Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
