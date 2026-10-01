# Routing security and IPv6 — SPK

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **Spark New Zealand Trading Limited** (ORG-SNZT1-AP) — 16 ASNs; 74 IPv4 blocks; 4 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-SNZT1-AP (retrieved 2026-10-01T01:42:13Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 16 | APNIC RDAP |
| IPv4 blocks registered | 74 | APNIC RDAP |
| IPv6 blocks registered | 4 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 653 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 91 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 13 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 1 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 23 / 0 / 721 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 16 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS2569 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS2570 | NZ | 23 | 1 | 0/0/24 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-09-29 | seen=2.4375, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-09-29 |
| AS4648 | NZ | 166 | 6 | 19/0/153 | none | seen=2, filter_rate=0.428266 (28-day); series date 2026-09-29 | seen=42.466667, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-09-29 |
| AS4771 | NZ | 444 | 77 | 4/0/517 | none | seen=57, filter_rate=0.04301 (28-day); series date 2026-09-29 | seen=18066.566667, capable_pc=0.204798, preferred_pc=0.089115 (30-day); series date 2026-09-29 |
| AS4834 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS9325 | NZ | 1 | 0 | 0/0/1 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=0.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2015-03-13 |
| AS17994 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2023-04-05 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2023-11-16 |
| AS18006 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS18348 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS18353 | NZ | 19 | 7 | 0/0/26 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-07-27 | seen=3.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-07-27 |
| AS38479 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2020-08-13 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-03-08 |
| AS38485 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS45222 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS133420 | NZ | 0 | 0 | 0/0/0 | none | seen=26, filter_rate=2.592223 (28-day); series date 2021-03-10 | seen=49.464286, capable_pc=0.072202, preferred_pc=0.0 (30-day); series date 2021-03-09 |
| AS133473 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS134444 | NZ | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2016-03-08 |

## Source queries

- AS2569: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS2569 (2026-10-01T01:42:17Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ2569 (2026-10-01T01:42:20Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ2569 (2026-10-01T01:42:21Z)
- AS2570: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS2570 (2026-10-01T01:42:23Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ2570 (2026-10-01T01:42:26Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ2570 (2026-10-01T01:42:27Z)
- AS4648: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS4648 (2026-10-01T01:42:29Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ4648 (2026-10-01T01:42:32Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ4648 (2026-10-01T01:42:34Z)
- AS4771: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS4771 (2026-10-01T01:42:36Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ4771 (2026-10-01T01:42:39Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ4771 (2026-10-01T01:42:41Z)
- AS4834: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS4834 (2026-10-01T01:42:43Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ4834 (2026-10-01T01:42:45Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ4834 (2026-10-01T01:42:46Z)
- AS9325: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9325 (2026-10-01T01:42:48Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ9325 (2026-10-01T01:42:51Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ9325 (2026-10-01T01:42:52Z)
- AS17994: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS17994 (2026-10-01T01:42:54Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ17994 (2026-10-01T01:42:57Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ17994 (2026-10-01T01:42:58Z)
- AS18006: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS18006 (2026-10-01T01:43:00Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ18006 (2026-10-01T01:43:03Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ18006 (2026-10-01T01:43:05Z)
- AS18348: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS18348 (2026-10-01T01:43:06Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ18348 (2026-10-01T01:43:09Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ18348 (2026-10-01T01:43:10Z)
- AS18353: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS18353 (2026-10-01T01:43:12Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ18353 (2026-10-01T01:43:15Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ18353 (2026-10-01T01:43:16Z)
- AS38479: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38479 (2026-10-01T01:43:18Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ38479 (2026-10-01T01:43:21Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ38479 (2026-10-01T01:43:22Z)
- AS38485: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38485 (2026-10-01T01:43:24Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ38485 (2026-10-01T01:43:27Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ38485 (2026-10-01T01:43:28Z)
- AS45222: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS45222 (2026-10-01T01:43:31Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ45222 (2026-10-01T01:43:33Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ45222 (2026-10-01T01:43:35Z)
- AS133420: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133420 (2026-10-01T01:43:37Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ133420 (2026-10-01T01:43:39Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ133420 (2026-10-01T01:43:41Z)
- AS133473: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133473 (2026-10-01T01:43:43Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ133473 (2026-10-01T01:43:45Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ133473 (2026-10-01T01:43:46Z)
- AS134444: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS134444 (2026-10-01T01:43:48Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=NZ134444 (2026-10-01T01:43:51Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=NZ134444 (2026-10-01T01:43:52Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
