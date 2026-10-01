# Routing security and IPv6 — SLC

Numbers only. Each figure lists its source, the exact URL queried and the UTC retrieval time.

## Registry holder(s) and allocations (APNIC RDAP)

- **SUPERLOOP (AUSTRALIA) PTY LTD** (ORG-SPL2-AP) — 24 ASNs; 77 IPv4 blocks; 6 IPv6 blocks. Source: https://rdap.apnic.net/entity/ORG-SPL2-AP (retrieved 2026-10-01T01:32:27Z)

## Totals

| Measure | Value | Source |
|---|---|---|
| ASNs held | 24 | APNIC RDAP |
| IPv4 blocks registered | 77 | APNIC RDAP |
| IPv6 blocks registered | 6 | APNIC RDAP |
| IPv4 prefixes routed (originated by these ASNs) | 234 | RIPEstat announced-prefixes |
| IPv6 prefixes routed | 17 | RIPEstat announced-prefixes |
| ROAs (VRPs) inside registered IPv4 blocks | 267 | https://rpki.cloudflare.com/rpki.json (version 2026-10-01T01:02:14Z; retrieved 2026-10-01T01:27:49Z) |
| ROAs (VRPs) inside registered IPv6 blocks | 4 | same |
| RPKI status of announcements, valid / invalid / not-found (counted per origin-ASN + prefix pair) | 226 / 0 / 27 | route-origin validation (RFC 6811) of RIPEstat prefixes against the RPKI data set above |
| ASNs with an ASPA object | 0 of 24 | https://rpki.cloudflare.com/rpki.json (`aspas`) |
| MANRS participation | not collected | manrs.org returned a bot challenge (HTTP 403) to automated requests on 2026-10-01 |

## Per ASN

| ASN | Economy | Routed v4 | Routed v6 | RPKI valid/invalid/not-found | ASPA | APNIC Labs ROV (I-ROV) | APNIC Labs IPv6 |
|---|---|---|---|---|---|---|---|
| AS7631 | AU | 0 | 0 | 0/0/0 | none | seen=4, filter_rate=100.0 (28-day); series date 2023-09-08 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2023-09-08 |
| AS9499 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2018-12-27 |
| AS9549 | AU | 0 | 0 | 0/0/0 | none | seen=77, filter_rate=43.502825 (28-day); series date 2020-09-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2019-07-15 |
| AS10143 | AU | 79 | 12 | 82/0/9 | none | seen=3919, filter_rate=99.542799 (28-day); series date 2026-09-29 | seen=481.633333, capable_pc=21.683161, preferred_pc=19.959859 (30-day); series date 2026-09-29 |
| AS10223 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2024-06-02 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2024-06-11 |
| AS17438 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS17498 | AU | 0 | 0 | 0/0/0 | none | seen=10, filter_rate=100.0 (28-day); series date 2020-08-25 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-03-17 |
| AS17829 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-02-29 |
| AS17907 | AU | 0 | 0 | 0/0/0 | none | seen=1, filter_rate=100.0 (28-day); series date 2023-06-02 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2023-06-02 |
| AS18201 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2020-09-16 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-09-16 |
| AS23677 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2020-06-10 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2019-04-28 |
| AS23935 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 2020-06-17 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-06-17 |
| AS24001 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS24093 | AU | 0 | 0 | 0/0/0 | none | seen=1, filter_rate=100.0 (28-day); series date 2024-03-11 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2024-03-11 |
| AS24233 | AU | 6 | 0 | 6/0/0 | none | seen=156, filter_rate=100.0 (28-day); series date 2026-09-29 | seen=46.233333, capable_pc=3.965393, preferred_pc=3.749099 (30-day); series date 2026-09-29 |
| AS24240 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS38167 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=4.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2015-07-07 |
| AS38195 | AU | 151 | 5 | 138/0/18 | none | seen=54244, filter_rate=99.081228 (28-day); series date 2026-09-29 | seen=5935.6, capable_pc=40.550239, preferred_pc=36.058697 (30-day); series date 2026-09-29 |
| AS38570 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.25, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2019-01-14 |
| AS55411 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2020-04-02 |
| AS131185 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS132109 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS133123 | AU | 0 | 0 | 0/0/0 | none | seen=0, filter_rate=0.0 (28-day); series date 1970-01-01 | no data |
| AS133389 | AU | 0 | 0 | 0/0/0 | none | seen=1, filter_rate=100.0 (28-day); series date 2026-02-09 | seen=1.0, capable_pc=0.0, preferred_pc=0.0 (30-day); series date 2026-02-09 |

## Source queries

- AS7631: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS7631 (2026-10-01T01:32:31Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU7631 (2026-10-01T01:32:34Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU7631 (2026-10-01T01:32:36Z)
- AS9499: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9499 (2026-10-01T01:32:38Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9499 (2026-10-01T01:32:41Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9499 (2026-10-01T01:32:42Z)
- AS9549: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS9549 (2026-10-01T01:32:44Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU9549 (2026-10-01T01:32:47Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU9549 (2026-10-01T01:32:48Z)
- AS10143: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS10143 (2026-10-01T01:32:50Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU10143 (2026-10-01T01:32:53Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU10143 (2026-10-01T01:32:54Z)
- AS10223: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS10223 (2026-10-01T01:32:56Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU10223 (2026-10-01T01:33:00Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU10223 (2026-10-01T01:33:01Z)
- AS17438: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS17438 (2026-10-01T01:33:03Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU17438 (2026-10-01T01:33:06Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU17438 (2026-10-01T01:33:07Z)
- AS17498: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS17498 (2026-10-01T01:33:09Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU17498 (2026-10-01T01:33:12Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU17498 (2026-10-01T01:33:13Z)
- AS17829: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS17829 (2026-10-01T01:33:15Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU17829 (2026-10-01T01:33:18Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU17829 (2026-10-01T01:33:20Z)
- AS17907: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS17907 (2026-10-01T01:33:21Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU17907 (2026-10-01T01:33:24Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU17907 (2026-10-01T01:33:26Z)
- AS18201: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS18201 (2026-10-01T01:33:28Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU18201 (2026-10-01T01:33:31Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU18201 (2026-10-01T01:33:32Z)
- AS23677: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS23677 (2026-10-01T01:33:34Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU23677 (2026-10-01T01:33:37Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU23677 (2026-10-01T01:33:38Z)
- AS23935: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS23935 (2026-10-01T01:33:40Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU23935 (2026-10-01T01:33:43Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU23935 (2026-10-01T01:33:44Z)
- AS24001: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24001 (2026-10-01T01:33:46Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24001 (2026-10-01T01:33:49Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24001 (2026-10-01T01:33:50Z)
- AS24093: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24093 (2026-10-01T01:33:52Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24093 (2026-10-01T01:33:55Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24093 (2026-10-01T01:33:56Z)
- AS24233: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24233 (2026-10-01T01:33:58Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24233 (2026-10-01T01:34:01Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24233 (2026-10-01T01:34:02Z)
- AS24240: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS24240 (2026-10-01T01:34:04Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU24240 (2026-10-01T01:34:07Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU24240 (2026-10-01T01:34:08Z)
- AS38167: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38167 (2026-10-01T01:34:10Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU38167 (2026-10-01T01:34:13Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU38167 (2026-10-01T01:34:14Z)
- AS38195: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38195 (2026-10-01T01:34:16Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU38195 (2026-10-01T01:34:19Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU38195 (2026-10-01T01:34:21Z)
- AS38570: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS38570 (2026-10-01T01:34:23Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU38570 (2026-10-01T01:34:26Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU38570 (2026-10-01T01:34:27Z)
- AS55411: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS55411 (2026-10-01T01:34:30Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU55411 (2026-10-01T01:34:32Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU55411 (2026-10-01T01:34:34Z)
- AS131185: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS131185 (2026-10-01T01:34:36Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU131185 (2026-10-01T01:34:38Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU131185 (2026-10-01T01:34:39Z)
- AS132109: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS132109 (2026-10-01T01:34:41Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU132109 (2026-10-01T01:34:44Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU132109 (2026-10-01T01:34:45Z)
- AS133123: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133123 (2026-10-01T01:34:47Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU133123 (2026-10-01T01:34:50Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU133123 (2026-10-01T01:34:51Z)
- AS133389: prefixes https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS133389 (2026-10-01T01:34:53Z); ROV https://stats.labs.apnic.net/cgi-bin/rpki-json-table.pl?x=AU133389 (2026-10-01T01:34:56Z); IPv6 https://stats.labs.apnic.net/cgi-bin/json-table-v6.pl?x=AU133389 (2026-10-01T01:34:57Z)

APNIC Labs data: "(c) APNIC Pty/Ltd. re-use with attribution permitted". RIPEstat data used under the RIPEstat Service Terms and Conditions.
