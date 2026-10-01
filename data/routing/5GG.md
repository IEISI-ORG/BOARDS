# Routing security and IPv6 — 5GG

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **PENTANET LIMITED** (ORG-PPL10-AP) — 3 ASNs; 9 IPv4 blocks; 3 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-PPL10-AP (retrieved 2026-10-01T01:38:27Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 3 | APNIC RDAP |
| IPv4 blocks registered | 9 | APNIC RDAP |
| IPv6 blocks registered | 3 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 48 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 8 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 29 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 23 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 56 / 0 / 0 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 3 of 3 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS10214 | AU | 48 | 7 | 55/0/0 | providers: 9507, 137409 | seen=1430, filter_rate=56.343578 (28-day); series date 2026-09-29 | seen=381.966667, capable_pc=62.544725, preferred_pc=60.118684 (30-day); series date 2026-09-29 |
| AS132458 | AU | 0 | 1 | 1/0/0 | providers: 4826, 10214 | seen=1, filter_rate=100.0 (28-day); series date 2026-09-18 | seen=3.857143, capable_pc=41.666667, preferred_pc=41.666667 (30-day); series date 2020-02-11 |
| AS133895 | AU | 0 | 0 | 0/0/0 | providers: 10214 | seen=0, filter_rate=0.0 (28-day); series date 2020-09-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-03-20 |

## Source queries

- AS10214: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS10214 (2026-10-01T01:38:30Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU10214 (2026-10-01T01:38:33Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU10214 (2026-10-01T01:38:35Z)
- AS132458: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS132458 (2026-10-01T01:38:37Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU132458 (2026-10-01T01:38:40Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU132458 (2026-10-01T01:38:41Z)
- AS133895: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133895 (2026-10-01T01:38:43Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU133895 (2026-10-01T01:38:46Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU133895 (2026-10-01T01:38:47Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
