# Expiring One-Word Domains (102,203)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-102%2C203%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of expiring one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **102,203 domains** on the canonical page below.

**Last updated:** 2026-04-09  
**Canonical page:** `https://unique.domains/domains/expiring`  
**Best for:** investors, acquisition teams

---

<p align="center">
  <a href="https://unique.domains/domains/expiring?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=top_open_search"><b>Open live search</b></a> ·
  <a href="https://unique.domains/domains/expiring?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=top_create_radar"><b>Create Radar</b></a> ·
  <a href="https://unique.domains/domains/expiring?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=top_start_project"><b>Start a naming Project</b></a> ·
  <a href="./expiring.csv"><b>Download CSV</b></a> ·
  <a href="./expiring.json"><b>Download JSON</b></a> ·
  <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=top_methodology"><b>Methodology</b></a> ·
  <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=top_api_docs"><b>API docs</b></a>
</p>

## 📦 What this repository contains

This repository is the public extract for the exact Unique Domains search represented by `https://unique.domains/domains/expiring`.

### Files

- `expiring.csv` — public CSV extract (10,000 rows)
- `expiring.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract
- `assets/chart-demand-buckets.png` — generated demand-buckets chart

### Use this repo to

- inspect a public sample
- download CSV or JSON
- cite the dataset
- understand the fields and scoring inputs

### Use the live page to

- keep the exact search context
- search the full live catalog
- filter by price, demand, status, spelling risk, and fit
- save the exact search as a Radar
- turn the search into a founder Project

## 📊 Snapshot of the live catalog

![Demand buckets across the live search](./assets/chart-demand-buckets.png)

**Why this chart:** it gives a fast overview of the live search composition using the same preview payload that supplies the README counts.

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/expiring-oneword-domains/main/expiring.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status   | purchase_price | renewal_price | attractiveness | demand | length | registrar                                   |
| -------------------- | -------- | -------------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| diplomacy.me         | expiring | $402.50        | $27.99        | 73             | 13     | 9      | Dynadot Inc                                 |
| monetary.nl          | expiring | $3,400.70      | —             | 72             | 10     | 8      | The Registrar Company B.V.                  |
| funny.id             | expiring | —              | —             | 111            | 99     | 5      | PANDI Registrar                             |
| idea.us              | expiring | —              | —             | 88             | 99     | 4      | GoDaddy.com, LLC                            |
| idea.la              | expiring | —              | —             | 88             | 99     | 4      | GoDaddy.com, Inc.                           |
| idea.co              | expiring | —              | —             | 88             | 99     | 4      | GoDaddy.com, LLC                            |
| france.us            | expiring | —              | —             | 76             | 99     | 6      | IONOS SE                                    |
| wild.events          | expiring | —              | —             | 66             | 99     | 4      | Gandi SAS                                   |
| endorse.now          | expiring | —              | —             | 100            | 98     | 7      | Spaceship, Inc.                             |
| nonstop.asia         | expiring | —              | —             | 98             | 98     | 7      | GoDaddy.com, LLC                            |
| commercial.community | expiring | —              | —             | 91             | 98     | 10     | GoDaddy.com, LLC                            |
| cyan.lol             | expiring | —              | —             | 90             | 98     | 4      | TLD Registrar Solutions Ltd                 |
| apart.earth          | expiring | —              | —             | 78             | 98     | 5      | GoDaddy.com, LLC                            |
| brave.moe            | expiring | —              | —             | 76             | 98     | 5      | NameCheap, Inc.                             |
| awaken.id            | expiring | —              | —             | 76             | 98     | 6      | PANDI Registrar                             |
| bright.events        | expiring | —              | —             | 74             | 98     | 6      | GoDaddy.com, LLC                            |
| brandnew.energy      | expiring | —              | —             | 72             | 98     | 9      | NameCheap, Inc.                             |
| bahamas.us           | expiring | —              | —             | 70             | 98     | 7      | GoDaddy.com, LLC                            |
| can.asia             | expiring | —              | —             | 68             | 98     | 3      | Alibaba Cloud Computing (Beijing) Co., Ltd. |
| shit.garden          | expiring | —              | —             | 64             | 98     | 4      | Porkbun                                     |

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- The live product contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Expiring One-Word Domains*. Version 2026-04-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live search](https://unique.domains/domains/expiring?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=related_pricing)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `hello@unique.domains`
