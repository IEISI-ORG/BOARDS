# Routing security and IPv6 — SWP

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **Swoop Telecommunications Pty Ltd** (ORG-CC4-AP) — 3 ASNs; 6 IPv4 blocks; 1 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-CC4-AP (retrieved 2026-10-01T01:37:07Z)
- **Anycast Holdings Pty Ltd** (ORG-CIPL2-AP) — 9 ASNs; 32 IPv4 blocks; 10 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-CIPL2-AP (retrieved 2026-10-01T01:37:08Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 12 | APNIC RDAP |
| IPv4 blocks registered | 38 | APNIC RDAP |
| IPv6 blocks registered | 11 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 134 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 8 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 90 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 7 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 110 / 1 / 31 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 12 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS9224 | AU | 4 | 0 | 4/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-08-19 | seen=2.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-08-19 |
| AS17551 | AU | 39 | 3 | 39/0/3 | none | seen=5, filter_rate=0.08194 (28-day); series date 2026-09-29 | seen=810.2, capable_pc=17.436024, preferred_pc=15.687485 (30-day); series date 2026-09-29 |
| AS23874 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS24100 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS38330 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2024-02-14 | seen=22.4, capable_pc=0.446429, preferred_pc=0.14881 (30-day); series date 2024-02-12 |
| AS55811 | AU | 4 | 0 | 3/0/1 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-09-29 | seen=2.111111, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-09-29 |
| AS58511 | AU | 10 | 2 | 10/0/2 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-09-29 | seen=8.538462, capable_pc=1.801802, preferred_pc=0.0 (30-day); series date 2026-09-29 |
| AS132858 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS133556 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2024-03-13 | seen=6.137931, capable_pc=3.370787, preferred_pc=3.370787 (30-day); series date 2024-03-11 |
| AS134743 | AU | 47 | 1 | 23/0/25 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-09-29 | seen=25.333333, capable_pc=0.131579, preferred_pc=0.0 (30-day); series date 2026-09-29 |
| AS136037 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2022-08-19 | seen=4.962963, capable_pc=10.447761, preferred_pc=10.447761 (30-day); series date 2022-08-17 |
| AS137549 | AU | 30 | 2 | 31/1/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-09-29 | seen=46.5, capable_pc=0.215054, preferred_pc=0.143369 (30-day); series date 2026-09-29 |

## Source queries

- AS9224: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9224 (2026-10-01T01:37:11Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9224 (2026-10-01T01:37:14Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9224 (2026-10-01T01:37:16Z)
- AS17551: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS17551 (2026-10-01T01:37:18Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU17551 (2026-10-01T01:37:21Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU17551 (2026-10-01T01:37:22Z)
- AS23874: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS23874 (2026-10-01T01:37:24Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU23874 (2026-10-01T01:37:27Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU23874 (2026-10-01T01:37:28Z)
- AS24100: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24100 (2026-10-01T01:37:30Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24100 (2026-10-01T01:37:33Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24100 (2026-10-01T01:37:34Z)
- AS38330: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38330 (2026-10-01T01:37:36Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU38330 (2026-10-01T01:37:39Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU38330 (2026-10-01T01:37:40Z)
- AS55811: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS55811 (2026-10-01T01:37:42Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU55811 (2026-10-01T01:37:46Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU55811 (2026-10-01T01:37:47Z)
- AS58511: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS58511 (2026-10-01T01:37:49Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU58511 (2026-10-01T01:37:52Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU58511 (2026-10-01T01:37:54Z)
- AS132858: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS132858 (2026-10-01T01:37:56Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU132858 (2026-10-01T01:37:58Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU132858 (2026-10-01T01:38:00Z)
- AS133556: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133556 (2026-10-01T01:38:02Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU133556 (2026-10-01T01:38:05Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU133556 (2026-10-01T01:38:06Z)
- AS134743: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS134743 (2026-10-01T01:38:08Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU134743 (2026-10-01T01:38:11Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU134743 (2026-10-01T01:38:12Z)
- AS136037: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS136037 (2026-10-01T01:38:14Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU136037 (2026-10-01T01:38:18Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU136037 (2026-10-01T01:38:19Z)
- AS137549: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS137549 (2026-10-01T01:38:21Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU137549 (2026-10-01T01:38:24Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU137549 (2026-10-01T01:38:25Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
