# Routing security and IPv6 — CNU

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **CHORUS NEW ZEALAND LIMITED** (ORG-CNZL1-AP) — 2 ASNs; 1 IPv4 blocks; 1 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-CNZL1-AP (retrieved 2026-10-01T01:41:57Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 2 | APNIC RDAP |
| IPv4 blocks registered | 1 | APNIC RDAP |
| IPv6 blocks registered | 1 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 5 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 1 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 2 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 3 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 7 / 0 / 0 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 2 of 2 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS132898 | NZ | 5 | 1 | 6/0/0 | providers: 9790, 13335 | seen=0, filter_rate=0.0 (28-day); series date 2025-05-14 | seen=2.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2025-05-14 |
| AS152653 | NZ | 1 | 0 | 1/0/0 | providers: 55850 | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=2.5, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-07-23 |

## Source queries

- AS132898: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS132898 (2026-10-01T01:42:00Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ132898 (2026-10-01T01:42:03Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ132898 (2026-10-01T01:42:05Z)
- AS152653: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS152653 (2026-10-01T01:42:07Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ152653 (2026-10-01T01:42:09Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ152653 (2026-10-01T01:42:11Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
