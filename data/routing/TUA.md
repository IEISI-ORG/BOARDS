# Routing security and IPv6 — TUA

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **Simba Telecom Pte Ltd** (ORG-STPL31-AP) — 1 ASNs; 4 IPv4 blocks; 1 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-STPL31-AP (retrieved 2026-10-01T01:41:47Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 1 | APNIC RDAP |
| IPv4 blocks registered | 4 | APNIC RDAP |
| IPv6 blocks registered | 1 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 24 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 15 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 27 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 11 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 35 / 0 / 4 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 1 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS4817 | SG | 24 | 15 | 35/0/4 | none | seen=144, filter_rate=0.286522 (28-day); series date 2026-09-29 | seen=3938.733333, capable_pc=60.803812, preferred_pc=60.57108 (30-day); series date 2026-09-29 |

## Source queries

- AS4817: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS4817 (2026-10-01T01:41:50Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=SG4817 (2026-10-01T01:41:54Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=SG4817 (2026-10-01T01:41:55Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
