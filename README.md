# Available .REPAIR One-Word Domains (5,621,964)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C282%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C621%2C964%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .repair one-word domains from Unique Domains.

> **Important:** this repository is a **public 9,282-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,621,964 domains** on the canonical page below.

**Public extract:** 9,282 rows · **Live catalog:** 5,621,964 domains

**Last updated:** 2026-04-10  
**Canonical page:** `https://unique.domains/domains/tld/repair`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/repair?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./repair.csv">CSV</a> / <a href="./repair.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .REPAIR search](https://unique.domains/domains/tld/repair?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .REPAIR search](https://unique.domains/domains/tld/repair?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .REPAIR one-word domain catalog.

### Files

- `repair.csv` — public CSV extract (9,282 rows)
- `repair.json` — public JSON extract (9,282 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/repair-oneword-domains/main/repair.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| zero.repair       | available | $9.99     | $46.99        | 112            | 53     | 4      | name.com         |
| industrial.repair | resell    | $47.48    | —             | 62             | 25     | 10     | Spaceship, Inc.  |
| one.repair        | premium   | $250      | $250          | 132            | 51     | 3      | name.com         |
| alpha.repair      | available | $9.99     | $46.99        | 90             | 53     | 5      | name.com         |
| music.repair      | resell    | —         | —             | 84             | 56     | 5      | Sav.com, LLC     |
| travel.repair     | premium   | $520      | $520          | 115            | 48     | 6      | namecheap        |
| forge.repair      | available | $9.99     | $46.99        | 62             | 45     | 5      | name.com         |
| smart.repair      | resell    | —         | —             | 74             | 56     | 5      | Dynadot Inc      |
| green.repair      | premium   | $42.90    | $42.90        | 108            | 46     | 5      | namecheap        |
| event.repair      | available | $47.48    | —             | 96             | 44     | 5      | namecheap        |
| good.repair       | resell    | —         | —             | 82             | 55     | 4      | Sav.com, LLC     |
| pop.repair        | premium   | $250      | $250          | 82             | 43     | 3      | name.com         |
| food.repair       | available | $47.48    | —             | 94             | 44     | 4      | namecheap        |
| local.repair      | resell    | —         | —             | 102            | 54     | 5      | GoDaddy.com, LLC |
| first.repair      | premium   | $500      | $500          | 80             | 42     | 5      | name.com         |
| deep.repair       | available | $9.99     | $46.99        | 72             | 42     | 4      | name.com         |
| ada.repair        | resell    | —         | —             | 62             | 53     | 3      | GoDaddy.com, LLC |
| mark.repair       | premium   | $500      | $500          | 66             | 42     | 4      | name.com         |
| review.repair     | available | $47.48    | —             | 94             | 41     | 6      | namecheap        |
| find.repair       | resell    | —         | —             | 110            | 50     | 4      | Sav.com, LLC     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 9,282-row public sample | 5,621,964 live domains                           |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/repair?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/repair?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=related_pricing)

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
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REPAIR One-Word Domains*. Version 2026-04-10. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REPAIR page](https://unique.domains/domains/tld/repair?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
