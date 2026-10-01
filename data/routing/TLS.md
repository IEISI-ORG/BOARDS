# Routing security and IPv6 — TLS

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **Telstra Limited** (ORG-TC6-AP) — 14 ASNs; 95 IPv4 blocks; 3 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-TC6-AP (retrieved 2026-10-01T01:27:51Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 14 | APNIC RDAP |
| IPv4 blocks registered | 95 | APNIC RDAP |
| IPv6 blocks registered | 3 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 775 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 9 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 152 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 186 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 613 / 0 / 171 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 3 of 14 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS1221 | AU | 281 | 2 | 126/0/157 | providers: 4637 | seen=609144, filter_rate=99.585567 (28-day); series date 2026-09-29 | seen=81748.933333, capable_pc=82.361727, preferred_pc=79.708563 (30-day); series date 2026-09-29 |
| AS4632 | AU | 0 | 0 | 0/0/0 | providers: 1221 | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS9514 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS37978 | AU | 14 | 0 | 14/0/0 | none | seen=58, filter_rate=100.0 (28-day); series date 2026-09-29 | seen=6.434783, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-09-29 |
| AS132029 | AU | 14 | 1 | 1/0/14 | none | seen=1, filter_rate=100.0 (28-day); series date 2026-07-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-07-01 |
| AS132292 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS133859 | AU | 1 | 0 | 1/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-08-31 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-08-31 |
| AS133931 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS135083 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS135599 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS135887 | AU | 465 | 6 | 471/0/0 | providers: 1221 | seen=30772, filter_rate=99.569649 (28-day); series date 2026-09-29 | seen=3903.733333, capable_pc=0.660906, preferred_pc=0.086242 (30-day); series date 2026-09-29 |
| AS141886 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS149288 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS150689 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |

## Source queries

- AS1221: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS1221 (2026-10-01T01:27:59Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU1221 (2026-10-01T01:28:02Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU1221 (2026-10-01T01:28:03Z)
- AS4632: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS4632 (2026-10-01T01:28:05Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU4632 (2026-10-01T01:28:08Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU4632 (2026-10-01T01:28:09Z)
- AS9514: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9514 (2026-10-01T01:28:12Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9514 (2026-10-01T01:28:14Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9514 (2026-10-01T01:28:16Z)
- AS37978: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS37978 (2026-10-01T01:28:18Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU37978 (2026-10-01T01:28:21Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU37978 (2026-10-01T01:28:23Z)
- AS132029: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS132029 (2026-10-01T01:28:25Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU132029 (2026-10-01T01:28:27Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU132029 (2026-10-01T01:28:29Z)
- AS132292: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS132292 (2026-10-01T01:28:31Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU132292 (2026-10-01T01:28:33Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU132292 (2026-10-01T01:28:35Z)
- AS133859: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133859 (2026-10-01T01:28:37Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU133859 (2026-10-01T01:28:39Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU133859 (2026-10-01T01:28:41Z)
- AS133931: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133931 (2026-10-01T01:28:43Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU133931 (2026-10-01T01:28:46Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU133931 (2026-10-01T01:28:47Z)
- AS135083: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS135083 (2026-10-01T01:28:49Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU135083 (2026-10-01T01:28:52Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU135083 (2026-10-01T01:28:53Z)
- AS135599: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS135599 (2026-10-01T01:28:55Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU135599 (2026-10-01T01:28:58Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU135599 (2026-10-01T01:28:59Z)
- AS135887: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS135887 (2026-10-01T01:29:01Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU135887 (2026-10-01T01:29:04Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU135887 (2026-10-01T01:29:06Z)
- AS141886: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS141886 (2026-10-01T01:29:08Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU141886 (2026-10-01T01:29:11Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU141886 (2026-10-01T01:29:12Z)
- AS149288: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS149288 (2026-10-01T01:29:14Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU149288 (2026-10-01T01:29:16Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU149288 (2026-10-01T01:29:18Z)
- AS150689: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS150689 (2026-10-01T01:29:20Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU150689 (2026-10-01T01:29:22Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU150689 (2026-10-01T01:29:24Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
