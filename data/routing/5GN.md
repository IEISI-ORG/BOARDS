# Routing security and IPv6 — 5GN

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **5G NETWORK OPERATIONS PTY LTD** (ORG-NOPL2-AP) — 18 ASNs; 52 IPv4 blocks; 16 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-NOPL2-AP (retrieved 2026-10-01T01:39:07Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 18 | APNIC RDAP |
| IPv4 blocks registered | 52 | APNIC RDAP |
| IPv6 blocks registered | 16 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 141 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 19 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 87 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 29 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 139 / 1 / 21 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 18 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS9412 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS9667 | AU | 8 | 0 | 8/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-03-04 | seen=1.25, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-03-04 |
| AS9736 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS17467 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS18099 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS24330 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS24446 | AU | 16 | 1 | 17/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2025-08-25 | seen=2.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2025-08-25 |
| AS24557 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2016-10-04 |
| AS38318 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS38877 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS45214 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS56163 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2020-08-24 | seen=1.357143, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-06-22 |
| AS63956 | AU | 82 | 8 | 73/1/16 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-09-28 | seen=2.733333, capable_pc=4.878049, preferred_pc=0.0 (30-day); series date 2026-09-28 |
| AS132393 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2018-05-05 |
| AS133332 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.2, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-02-08 |
| AS133480 | AU | 35 | 10 | 40/0/5 | none | seen=0, filter_rate=0.0 (28-day); series date 2026-09-29 | seen=13.896552, capable_pc=1.488834, preferred_pc=1.488834 (30-day); series date 2026-09-29 |
| AS134441 | AU | 1 | 0 | 1/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2024-10-03 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2024-10-03 |
| AS136811 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |

## Source queries

- AS9412: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9412 (2026-10-01T01:39:12Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9412 (2026-10-01T01:39:15Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9412 (2026-10-01T01:39:16Z)
- AS9667: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9667 (2026-10-01T01:39:18Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9667 (2026-10-01T01:39:21Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9667 (2026-10-01T01:39:22Z)
- AS9736: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9736 (2026-10-01T01:39:24Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9736 (2026-10-01T01:39:27Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9736 (2026-10-01T01:39:28Z)
- AS17467: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS17467 (2026-10-01T01:39:30Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU17467 (2026-10-01T01:39:33Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU17467 (2026-10-01T01:39:34Z)
- AS18099: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS18099 (2026-10-01T01:39:36Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU18099 (2026-10-01T01:39:39Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU18099 (2026-10-01T01:39:40Z)
- AS24330: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24330 (2026-10-01T01:39:42Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24330 (2026-10-01T01:39:45Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24330 (2026-10-01T01:39:46Z)
- AS24446: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24446 (2026-10-01T01:39:49Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24446 (2026-10-01T01:39:52Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24446 (2026-10-01T01:39:53Z)
- AS24557: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24557 (2026-10-01T01:39:55Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24557 (2026-10-01T01:40:18Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24557 (2026-10-01T01:40:19Z)
- AS38318: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38318 (2026-10-01T01:40:21Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU38318 (2026-10-01T01:40:24Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU38318 (2026-10-01T01:40:30Z)
- AS38877: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38877 (2026-10-01T01:40:32Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU38877 (2026-10-01T01:40:50Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU38877 (2026-10-01T01:40:51Z)
- AS45214: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS45214 (2026-10-01T01:40:53Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU45214 (2026-10-01T01:40:58Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU45214 (2026-10-01T01:40:59Z)
- AS56163: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS56163 (2026-10-01T01:41:01Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU56163 (2026-10-01T01:41:04Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU56163 (2026-10-01T01:41:06Z)
- AS63956: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS63956 (2026-10-01T01:41:09Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU63956 (2026-10-01T01:41:12Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU63956 (2026-10-01T01:41:14Z)
- AS132393: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS132393 (2026-10-01T01:41:16Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU132393 (2026-10-01T01:41:18Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU132393 (2026-10-01T01:41:20Z)
- AS133332: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133332 (2026-10-01T01:41:22Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU133332 (2026-10-01T01:41:25Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU133332 (2026-10-01T01:41:26Z)
- AS133480: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133480 (2026-10-01T01:41:28Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU133480 (2026-10-01T01:41:31Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU133480 (2026-10-01T01:41:33Z)
- AS134441: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS134441 (2026-10-01T01:41:35Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU134441 (2026-10-01T01:41:38Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU134441 (2026-10-01T01:41:39Z)
- AS136811: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS136811 (2026-10-01T01:41:41Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU136811 (2026-10-01T01:41:44Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU136811 (2026-10-01T01:41:45Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
