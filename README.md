# Available .SPACE One-Word Domains (77,144)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-77%2C144%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .space one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **77,144 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 77,144 domains · **Median ask:** $269.79 · **High-demand under $2,500:** 343

**Last updated:** 2026-08-13
**Canonical page:** `https://unique.domains/domains/tld/space`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/space?utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./space.csv">CSV</a> / <a href="./space.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SPACE search](https://unique.domains/domains/tld/space?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SPACE search](https://unique.domains/domains/tld/space?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SPACE one-word domain catalog.

### Files

- `space.csv`, public CSV extract (1,000 rows)
- `space.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/space-oneword-domains/main/space.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| content.space    | available | —         | —             | high           | low    | 7      | —                                                         |
| sums.space       | available | $4.99     | —             | low            | low    | 4      | name.com                                                  |
| justintime.space | resell    | $4.99     | —             | medium         | low    | 12     | West263 International Limited                             |
| ixc.space        | premium   | $81.25    | $325          | low            | low    | 3      | namecheap                                                 |
| bifid.space      | available | $0.98     | $32.48        | medium         | low    | 5      | namecheap                                                 |
| lunar.space      | resell    | —         | —             | high           | low    | 5      | West263 International Limited                             |
| BRAS.space       | premium   | $175      | $700          | high           | low    | 4      | namecheap                                                 |
| clxxv.space      | available | $0.98     | $32.48        | low            | low    | 5      | namecheap                                                 |
| access.space     | resell    | —         | —             | high           | medium | 6      | DNSPod, Inc.                                              |
| draw.space       | premium   | $3,500    | $14,000       | high           | low    | 4      | namecheap                                                 |
| coldly.space     | available | $3.99     | $34.99        | medium         | low    | 6      | namesilo                                                  |
| wraith.space     | resell    | —         | —             | medium         | high   | 6      | Go Daddy, LLC                                             |
| duty.space       | premium   | $350      | $1,400        | medium         | low    | 4      | namecheap                                                 |
| mugup.space      | available | $0.98     | $32.48        | medium         | low    | 6      | namecheap                                                 |
| meaning.space    | resell    | —         | —             | high           | low    | 7      | Global Domains International, Inc. DBA DomainCostClub.com |
| fine.space       | premium   | $325      | $1,300        | high           | low    | 4      | namecheap                                                 |
| septet.space     | available | $0.98     | $32.48        | low            | low    | 6      | namecheap                                                 |
| rocketry.space   | resell    | —         | —             | medium         | high   | 8      | Porkbun, LLC                                              |
| hand.space       | premium   | $1,750    | $7,000        | high           | low    | 4      | namecheap                                                 |
| texted.space     | available | $4.99     | —             | medium         | low    | 6      | name.com                                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 77,144 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 343 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/space?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/space?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set of .space domain names leans toward everyday words and short compound phrases rather than acronyms or invented strings. Names such as creating.space, chaitea.space, and Googler.space show the range: single dictionary words, two-word blends, and brand-style coinages. With a median ask near $362 across 75,942 names, pricing sits low enough for founders to shortlist multiple options, while the size of the set gives investors room to compare word quality against ask price before committing to any single name.

- 75,942 one-word .space domain names in this selection
- Median ask near $362 across the set
- Everyday brandable terms: criteria, goodday, memorize, chaitea
- Compare pricing and renewal before shortlisting a name

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SPACE One-Word Domains*. Version 2026-08-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SPACE page](https://unique.domains/domains/tld/space?utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_space_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
