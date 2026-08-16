# Available .LEGAL One-Word Domains (15,217)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C217%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .legal one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,217 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,217 domains · **Median ask:** $13.41 · **High-demand under $2,500:** 1

**Last updated:** 2026-08-16
**Canonical page:** `https://unique.domains/domains/tld/legal`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/legal?utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./legal.csv">CSV</a> / <a href="./legal.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LEGAL search](https://unique.domains/domains/tld/legal?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LEGAL search](https://unique.domains/domains/tld/legal?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LEGAL one-word domain catalog.

### Files

- `legal.csv`, public CSV extract (1,000 rows)
- `legal.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/legal-oneword-domains/main/legal.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                          |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------------------ |
| ago.legal   | available | $9.99     | $92.99        | medium         | low    | 3      | name.com                                                           |
| apt.legal   | resell    | —         | —             | high           | low    | 3      | Domain Science Kutatási Szolgáltató Korlátolt Felelősségű Társaság |
| bud.legal   | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                                                           |
| any.legal   | available | $9.99     | —             | high           | medium | 3      | name.com                                                           |
| big.legal   | resell    | —         | —             | high           | medium | 3      | Sav.com, LLC                                                       |
| lol.legal   | premium   | $242      | $242          | high           | low    | 3      | namesilo                                                           |
| bce.legal   | available | $9.99     | —             | medium         | low    | 3      | name.com                                                           |
| dna.legal   | resell    | —         | —             | high           | medium | 3      | Porkbun LLC                                                        |
| arab.legal  | premium   | $242      | $242          | low            | low    | 4      | namesilo                                                           |
| cry.legal   | available | $9.99     | —             | high           | low    | 3      | name.com                                                           |
| hot.legal   | resell    | —         | —             | high           | low    | 3      | Porkbun LLC                                                        |
| what.legal  | premium   | $242      | $242          | high           | low    | 4      | namesilo                                                           |
| DJI.legal   | available | $9.99     | —             | high           | low    | 3      | name.com                                                           |
| sue.legal   | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC                                                   |
| blink.legal | premium   | $500      | —             | high           | medium | 5      | name.com                                                           |
| fit.legal   | available | $9.99     | —             | high           | medium | 3      | name.com                                                           |
| xxx.legal   | resell    | —         | —             | low            | medium | 3      | GoDaddy.com, LLC                                                   |
| price.legal | premium   | $242      | $242          | medium         | low    | 5      | namesilo                                                           |
| hum.legal   | available | $9.99     | —             | high           | low    | 3      | name.com                                                           |
| you.legal   | resell    | —         | —             | high           | medium | 3      | Sav.com, LLC                                                       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,217 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 1 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/legal?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/legal?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=related_pricing)

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

This set contains one-word .legal domain names built around law, compliance, and professional services themes. Names range from playful phrases like bonappetit.legal to direct terms like ladies.legal and goodnews.legal, giving both investors and founders a wide net to work from. With a median asking price near $15, entry cost across this selection stays low relative to legacy TLDs, though renewal and long-term positioning should still guide any decision. When comparing these domains, focus on clarity, memorability, and how well the name signals trust for a legal or compliance-focused audience.

- 11,634 one-word .legal domains in this selection
- Median asking price near $15 across the set
- Names span legal, compliance, and professional themes
- Updated daily to reflect current pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LEGAL One-Word Domains*. Version 2026-08-16. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LEGAL page](https://unique.domains/domains/tld/legal?utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_legal_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
