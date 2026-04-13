# Available .CHANNEL One-Word Domains (5,173)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-5%2C173%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C173%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .channel one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 5,173 rows · **Live catalog:** 5,173 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/tld/channel`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/channel?utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./channel.csv">CSV</a> / <a href="./channel.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CHANNEL search](https://unique.domains/domains/tld/channel?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CHANNEL search](https://unique.domains/domains/tld/channel?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CHANNEL one-word domain catalog.

### Files

- `channel.csv` — public CSV extract (5,173 rows)
- `channel.json` — public JSON extract (5,173 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/channel-oneword-domains/main/channel.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| adobe.channel      | available | $16.48    | —             | 72             | 69     | 5      | namecheap       |
| flow.channel       | resell    | —         | —             | 78             | 67     | 4      | Porkbun LLC     |
| mac.channel        | premium   | $73.75    | —             | 84             | 82     | 3      | name.com        |
| canon.channel      | available | $19.99    | —             | 70             | 67     | 5      | name.com        |
| you.channel        | resell    | —         | —             | 74             | 49     | 3      | Porkbun LLC     |
| mint.channel       | premium   | $311.25   | —             | 72             | 78     | 4      | name.com        |
| nationwide.channel | available | $16.48    | —             | 76             | 66     | 10     | namecheap       |
| trade.channel      | resell    | —         | —             | 82             | 46     | 5      | Spaceship, Inc. |
| loop.channel       | premium   | $311.25   | —             | 72             | 77     | 4      | name.com        |
| jeep.channel       | available | $16.48    | —             | 69             | 66     | 4      | namecheap       |
| craft.channel      | resell    | —         | —             | 70             | 42     | 5      | Spaceship, Inc. |
| name.channel       | premium   | $623.75   | —             | 82             | 76     | 4      | name.com        |
| priceless.channel  | available | $16.48    | —             | 79             | 65     | 9      | namecheap       |
| revelation.channel | resell    | —         | —             | 70             | 21     | 10     | Dynadot LLC.    |
| fire.channel       | premium   | $623.75   | —             | 70             | 75     | 4      | name.com        |
| artistry.channel   | available | $16.48    | —             | 82             | 63     | 8      | namecheap       |
| patriotic.channel  | resell    | —         | —             | 76             | 9      | 9      | Dynadot LLC.    |
| with.channel       | premium   | $623.75   | —             | 69             | 74     | 4      | name.com        |
| dowjones.channel   | available | $16.48    | —             | 80             | 63     | 9      | namecheap       |
| impact.channel     | premium   | $311.25   | —             | 74             | 73     | 6      | name.com        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 5,173-row public sample | 5,173 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/channel?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/channel?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .CHANNEL One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CHANNEL page](https://unique.domains/domains/tld/channel?utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_channel_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
