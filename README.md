# BOARDS — Technical expertise on ASX and NZX telco and digital-infrastructure boards

> **Disclaimer.** Written by AI, semi-supervised, from public data. It will contain errors. Every fact cites a public source — check it there. Report corrections as a GitHub issue; they will be pursued with vigour.

Evidence-based record of the technical backgrounds of directors of listed telecommunications and
digital-infrastructure operators in Australia and New Zealand.

- **Report:** [`update_report.md`](update_report.md) — coverage, level distribution by board, directors at
  Level 4 and above, company skills matrices, and verification of claims. The level system is explained
  in Appendix A of the report.
- **Director table:** [`data/directors.csv`](data/directors.csv) — 68 directors with a verified level.
- **Per-company checks:** [`data/cv/`](data/cv/) — each director's degrees, career evidence, level and grade.
- **Company skills matrices:** [`data/skill_matrices/`](data/skill_matrices/).
- **Sources:** [`data/src/`](data/src/) — for each source document: URL, date, evidence tier and the
  extracts relied on.

## Corrections

Corrections are welcome. Open a GitHub issue (or a pull request) with the public source that shows the
error. A correction is applied only when its source is public, so that anyone — person or AI agent —
can check it.

## Access for people and AI agents

All data is published as plain files at stable paths so that people and AI agents can read it without
logging in:

| File | Format | Contents |
|---|---|---|
| `data/directors.csv`, `data/directors.json` | CSV / JSON | One row per board seat with a verified level |
| `data/cv/<TICKER>.md` | Markdown | Degrees, career evidence, level and grade per director |
| `data/skill_matrices/<TICKER>_<FY>.md` | Markdown | Each company's published skills matrix |
| `data/src/<TICKER>_<DOC>.md` | Markdown | Source URLs, dates, evidence tier and extracts |

Raw URLs follow the pattern `https://raw.githubusercontent.com/IEISI-ORG/BOARDS/main/<path>`.

**Data dictionary (`directors.csv` / `directors.json`):** `exchange` (ASX, NZX/ASX); `ticker`; `company`;
`cohort` (ASX300, SmallCap, NZ); `director`; `independent` (Y/N, per the company's own classification);
`level` (1–6, see Appendix A of the report); `evidence_grade` (always V in published data); `sources`
(short names of the documents relied on; full URLs in `data/src/`).

## Source access and terms of use

Before using any website or API we check its terms of use and `robots.txt`. If they prohibit automated
or AI-agent access, we record that and stop using the source; if we find no prohibition, we record that
and use it. The register is in [`data/ACCESS_POLICY.md`](data/ACCESS_POLICY.md). For example, the ASX
website's terms prohibit robots and scrapers, so ASX pages are no longer accessed automatically.

## Why there is no LinkedIn data

Only sources that AI agents can read openly and lawfully are used. LinkedIn does not meet that test:

- LinkedIn's `robots.txt` (https://www.linkedin.com/robots.txt) states: *"The use of robots or other
  automated means to access LinkedIn without the express permission of LinkedIn is strictly
  prohibited."*
- Logged-out automated requests to LinkedIn profile pages return HTTP status 999 (tested 1 October 2026).
- Profile content shown only to logged-in members is not public, and profiles are self-reported.

For commentary on LinkedIn's User Agreement and AI agents, see Stan Robinson, Jr.'s post:
https://www.linkedin.com/posts/stanrobinson_linkedintips-aiinbusiness-aiagents-share-7361444705626124290-h1hJ/

As a result, directors' careers are recorded only as far as company filings, exchange announcements,
regulator documents, official web pages and reputable press describe them. Where a level could be higher
with better evidence, the per-company file says what public evidence would change it.

## Earlier classification

The per-company files compare each director's level with an earlier, unpublished classification
("report", "old tier", tiers A–D). Those references are kept to show what changed; the earlier document
itself is not published because it contained unverified statements.

## Source rule

Every fact is taken from a source that anyone can open without logging in (company filings, exchange
announcements, regulator documents, official web pages, reputable press). Only scores graded **V
(verified)** are published. The report is informational: it records evidence and counts it, and does not
make recommendations.

## Scope

Companies listed on the ASX or NZX that run their own internet-connected network or data-centre
services.

The check that a company actually runs internet-connected services is that it holds Internet number
resources — IP addresses and/or an Autonomous System Number (ASN) — from a Regional Internet Registry
(APNIC, the registry for the Asia-Pacific region including Australia and New Zealand), in its own name or a subsidiary's. Without number resources a
company cannot operate its own presence on the internet. The registry record for each company is
listed in the report's coverage table and can be checked at https://rdap.apnic.net/.

Registry membership is a check, not the reason for inclusion: many banks, retailers and energy companies
also hold number resources for their own corporate networks. Resellers that do not run their own
network, software companies and contractors are excluded.

## Coverage

The dataset is updated as more boards are checked. The coverage table at the top of the report shows
which companies are complete, in progress or not yet started.

## Licence

CC BY 4.0 for the text and data; quoted third-party extracts remain with their owners. See
[`LICENSE.md`](LICENSE.md).

*Last exported: 2026-10-01.*
