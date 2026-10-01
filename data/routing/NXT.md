# Routing security and IPv6 — NXT

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **NEXTDC Limited** (ORG-NL21-AP) — 2 ASNs; 3 IPv4 blocks; 2 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-NL21-AP (retrieved 2026-10-01T01:34:58Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 2 | APNIC RDAP |
| IPv4 blocks registered | 3 | APNIC RDAP |
| IPv6 blocks registered | 2 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 8 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 1 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 0 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 0 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 0 / 0 / 9 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 2 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS56263 | AU | 2 | 0 | 0/0/2 | none | seen=1, filter_rate=50.0 (28-day); series date 2026-09-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-09-01 |
| AS134138 | AU | 6 | 1 | 0/0/7 | none | seen=1, filter_rate=100.0 (28-day); series date 2026-03-13 | seen=2.0, capable_pc=50.0, preferred_pc=0.0 (30-day); series date 2026-07-30 |

## Company-stated network services

NEXTDC describes its interconnection services (AXON, data centre interconnects, intercapital Ethernet, peering ports, cloud on-ramps) at https://www.nextdc.com/interconnectivity (retrieved 2026-10-01). Summary: `data/src/NXT_WEB_interconnectivity.md`. The page states no ASN, prefix, RPKI or IPv6 figures.

## Source queries

- AS56263: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS56263 (2026-10-01T01:35:02Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU56263 (2026-10-01T01:35:04Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU56263 (2026-10-01T01:35:06Z)
- AS134138: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS134138 (2026-10-01T01:35:08Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU134138 (2026-10-01T01:35:10Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU134138 (2026-10-01T01:35:12Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
