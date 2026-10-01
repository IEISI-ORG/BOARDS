# Routing security and IPv6 — TPG

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **TPG Internet Pty Ltd** (ORG-TIPL2-AP) — 16 ASNs; 998 IPv4 blocks; 10 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-TIPL2-AP (retrieved 2026-10-01T01:29:26Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 16 | APNIC RDAP |
| IPv4 blocks registered | 998 | APNIC RDAP |
| IPv6 blocks registered | 10 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 4652 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 415 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 364 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 0 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 586 / 0 / 4481 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 16 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS7545 | AU | 4641 | 415 | 575/0/4481 | none | seen=992, filter_rate=0.4997 (28-day); series date 2026-09-29 | seen=27990.766667, capable_pc=12.664057, preferred_pc=10.660539 (30-day); series date 2026-09-29 |
| AS9476 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2020-08-28 | seen=6.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2018-05-16 |
| AS9722 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS9894 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS17999 | AU | 1 | 0 | 1/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS18374 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS18398 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS23718 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS23741 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS23745 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS23970 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS23997 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS24343 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS37987 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS38046 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS38066 | AU | 10 | 0 | 10/0/0 | none | seen=2, filter_rate=66.666667 (28-day); series date 2026-09-25 | seen=1.333333, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-09-25 |

## Source queries

- AS7545: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS7545 (2026-10-01T01:30:06Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU7545 (2026-10-01T01:30:09Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU7545 (2026-10-01T01:30:11Z)
- AS9476: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9476 (2026-10-01T01:30:28Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9476 (2026-10-01T01:30:30Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9476 (2026-10-01T01:30:32Z)
- AS9722: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9722 (2026-10-01T01:30:34Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9722 (2026-10-01T01:30:37Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9722 (2026-10-01T01:30:38Z)
- AS9894: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9894 (2026-10-01T01:30:40Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9894 (2026-10-01T01:30:42Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9894 (2026-10-01T01:30:44Z)
- AS17999: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS17999 (2026-10-01T01:30:45Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU17999 (2026-10-01T01:30:48Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU17999 (2026-10-01T01:30:49Z)
- AS18374: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS18374 (2026-10-01T01:30:52Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU18374 (2026-10-01T01:30:54Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU18374 (2026-10-01T01:30:56Z)
- AS18398: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS18398 (2026-10-01T01:30:57Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU18398 (2026-10-01T01:31:00Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU18398 (2026-10-01T01:31:01Z)
- AS23718: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS23718 (2026-10-01T01:31:03Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU23718 (2026-10-01T01:31:06Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU23718 (2026-10-01T01:31:07Z)
- AS23741: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS23741 (2026-10-01T01:31:09Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU23741 (2026-10-01T01:31:12Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU23741 (2026-10-01T01:31:13Z)
- AS23745: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS23745 (2026-10-01T01:31:15Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU23745 (2026-10-01T01:31:18Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU23745 (2026-10-01T01:31:19Z)
- AS23970: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS23970 (2026-10-01T01:31:21Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU23970 (2026-10-01T01:31:24Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU23970 (2026-10-01T01:31:25Z)
- AS23997: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS23997 (2026-10-01T01:31:27Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU23997 (2026-10-01T01:31:29Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU23997 (2026-10-01T01:31:30Z)
- AS24343: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24343 (2026-10-01T01:31:32Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24343 (2026-10-01T01:31:35Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24343 (2026-10-01T01:31:36Z)
- AS37987: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS37987 (2026-10-01T01:31:38Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU37987 (2026-10-01T01:31:41Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU37987 (2026-10-01T01:31:42Z)
- AS38046: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38046 (2026-10-01T01:31:44Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU38046 (2026-10-01T01:31:47Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU38046 (2026-10-01T01:31:48Z)
- AS38066: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38066 (2026-10-01T01:31:50Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU38066 (2026-10-01T01:31:53Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU38066 (2026-10-01T01:31:54Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
