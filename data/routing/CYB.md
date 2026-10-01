# Routing security and IPv6 — CYB (AUCyber, formerly Sovereign Cloud Holdings)

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **Sovereign Cloud Australia Pty Ltd** (ORG-SCAP1-AP) — 1 ASNs; 4 IPv4 blocks; 1 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-SCAP1-AP (retrieved 2026-10-01T01:38:55Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 1 | APNIC RDAP |
| IPv4 blocks registered | 4 | APNIC RDAP |
| IPv6 blocks registered | 1 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 6 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 2 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 8 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 2 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 8 / 0 / 0 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 1 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS137455 | AU | 6 | 2 | 8/0/0 | none | seen=1, filter_rate=100.0 (28-day); series date 2024-04-09 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2024-04-09 |

## Source queries

- AS137455: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS137455 (2026-10-01T01:39:01Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU137455 (2026-10-01T01:39:04Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU137455 (2026-10-01T01:39:05Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
