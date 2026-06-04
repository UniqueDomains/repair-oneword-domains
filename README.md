# Available .REPAIR One-Word Domains (12,225)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C225%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .repair one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,225 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,225 domains · **Median ask:** $14.06 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
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

- `repair.csv` — public CSV extract (1,000 rows)
- `repair.json` — public JSON extract (1,000 rows)
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

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar              |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------- |
| found.repair        | available | $9.99     | —             | 92             | 47     | 5      | name.com               |
| beyond.repair       | resell    | —         | —             | 87             | 49     | 6      | Name SRS AB            |
| fire.repair         | premium   | $242      | $242          | 80             | 74     | 4      | namesilo               |
| verify.repair       | available | $9.99     | —             | 80             | 42     | 6      | name.com               |
| intelligence.repair | resell    | —         | —             | 80             | 39     | 12     | Sav.com, LLC - 7       |
| best.repair         | premium   | $500      | —             | 82             | 55     | 4      | name.com               |
| action.repair       | available | $9.99     | —             | 128            | 40     | 6      | name.com               |
| pool.repair         | resell    | —         | —             | 66             | 39     | 4      | Go France Domains, LLC |
| sec.repair          | premium   | $242      | $242          | 60             | 37     | 3      | namesilo               |
| culture.repair      | available | $9.99     | —             | 98             | 40     | 7      | name.com               |
| scan.repair         | resell    | —         | —             | 90             | 38     | 4      | Porkbun LLC            |
| sip.repair          | premium   | $118.80   | $118.80       | 62             | 32     | 3      | namesilo               |
| eternal.repair      | available | $9.99     | $46.99        | 92             | 40     | 7      | name.com               |
| machine.repair      | resell    | —         | —             | 90             | 37     | 7      | Spaceship, Inc.        |
| monitor.repair      | premium   | $500      | —             | 64             | 31     | 7      | name.com               |
| Phil.repair         | available | $9.99     | —             | 78             | 40     | 4      | name.com               |
| call.repair         | resell    | —         | —             | 80             | 37     | 4      | Dynadot Inc            |
| gun.repair          | premium   | $242      | $242          | 56             | 31     | 3      | namesilo               |
| Flowers.repair      | available | $9.99     | —             | 74             | 40     | 7      | name.com               |
| legend.repair       | resell    | —         | —             | 72             | 33     | 6      | GoDaddy.com, LLC       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,225 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

These domains are one-word names on the .repair extension. The set includes concrete words, abstract words, and longer dictionary terms such as second.repair, clay.repair, idea.repair, own.repair, biological.repair, and teamwork.repair. When comparing these domains, focus on whether the word makes immediate sense with .repair, how easy it is to say and spell, and whether the pairing feels credible for a repair business or service. Shorter, clearer words usually read faster, but strong semantic fit matters more than novelty. If two names are similarly priced, the better choice is usually the one with cleaner meaning, lower ambiguity, and less chance of confusion with established brands.

- Prefer words that pair naturally with .repair
- Short, clear names are easier to remember
- Check whether the term feels commercial or abstract
- Avoid words that may invite brand confusion

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REPAIR One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REPAIR page](https://unique.domains/domains/tld/repair?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_repair_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
