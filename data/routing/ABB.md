# Routing security and IPv6 — ABB

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **Aussie Fibre Pty Ltd** (ORG-WNPL1-AP) — 4 ASNs; 27 IPv4 blocks; 4 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-WNPL1-AP (retrieved 2026-10-01T01:31:56Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 4 | APNIC RDAP |
| IPv4 blocks registered | 27 | APNIC RDAP |
| IPv6 blocks registered | 4 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 385 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 19 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 33 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 14 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 383 / 0 / 24 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 4 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS4764 | AU | 384 | 19 | 379/0/24 | none | seen=116588, filter_rate=98.713878 (28-day); series date 2026-09-29 | seen=14585.0, capable_pc=28.782082, preferred_pc=24.226031 (30-day); series date 2026-09-29 |
| AS23762 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2020-08-26 | seen=1.545455, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-03-02 |
| AS24243 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2020-08-25 | seen=1.666667, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2018-10-11 |
| AS136943 | AU | 2 | 2 | 4/0/0 | none | seen=3, filter_rate=100.0 (28-day); series date 2026-08-21 | seen=2.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-08-21 |

## Source queries

- AS4764: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS4764 (2026-10-01T01:32:00Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU4764 (2026-10-01T01:32:03Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU4764 (2026-10-01T01:32:05Z)
- AS23762: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS23762 (2026-10-01T01:32:08Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU23762 (2026-10-01T01:32:11Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU23762 (2026-10-01T01:32:13Z)
- AS24243: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24243 (2026-10-01T01:32:14Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24243 (2026-10-01T01:32:17Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24243 (2026-10-01T01:32:18Z)
- AS136943: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS136943 (2026-10-01T01:32:20Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU136943 (2026-10-01T01:32:23Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU136943 (2026-10-01T01:32:25Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
