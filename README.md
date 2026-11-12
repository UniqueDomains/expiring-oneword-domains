# Expiring One-Word Domains (52,244)

52,244 names in this list today, refreshed every night.

Live page: [unique.domains/domains/expiring](https://unique.domains/domains/expiring?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=top_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [expiring.csv](https://github.com/UniqueDomains/expiring-oneword-domains/raw/main/expiring.csv), 1,000 rows
- [expiring.json](https://github.com/UniqueDomains/expiring-oneword-domains/raw/main/expiring.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/expiring-oneword-domains/main/expiring.csv")
print(df.head())
```

## Sample rows

The first 20 rows of the file, in the file's order.

| domain            | status   | purchase_price | renewal_price | attractiveness | demand | length |
| ----------------- | -------- | -------------- | ------------- | -------------- | ------ | ------ |
| spotlight.yachts  | expiring | —              | —             | high           | high   | 9      |
| service.poker     | expiring | —              | —             | high           | high   | 7      |
| trump.clothing    | expiring | —              | —             | high           | low    | 5      |
| spanking.us       | expiring | —              | —             | high           | low    | 8      |
| signature.reviews | expiring | —              | —             | high           | low    | 9      |
| basics.news       | expiring | —              | —             | high           | low    | 6      |
| synthetic.care    | expiring | —              | —             | high           | low    | 9      |
| onto.email        | expiring | —              | —             | high           | low    | 4      |
| sobremesa.us      | expiring | —              | —             | high           | medium | 9      |
| phr.homes         | expiring | —              | —             | high           | low    | 3      |
| mode.discount     | expiring | —              | —             | high           | low    | 4      |
| shiny.partners    | expiring | —              | —             | high           | medium | 5      |
| remote.autos      | expiring | $684.64        | —             | high           | medium | 6      |
| astral.rent       | expiring | —              | —             | high           | low    | 6      |
| arcus.gay         | expiring | —              | —             | high           | low    | 5      |
| jacks.sh          | expiring | —              | —             | high           | low    | 5      |
| all.coach         | expiring | —              | —             | high           | medium | 3      |
| scully.app        | expiring | —              | —             | high           | low    | 6      |
| blithe.io         | expiring | —              | —             | high           | low    | 6      |
| ultimatum.io      | expiring | —              | —             | high           | low    | 9      |

## What is in the data

- `domain`: Fully qualified domain name.
- `status`: Current acquisition state for the domain in the public extract.
- `purchase_price`: Visible purchase price when available.
- `renewal_price`: Visible renewal price when available.
- `attractiveness`: Public composite naming band used as a decision-support signal.
- `demand`: Public buyer-pressure band when available.
- `length`: Character count without the TLD.
- `registrar`: Registrar name when known.
- `created_at`: Creation timestamp when known.
- `expires_at`: Expiry timestamp when known.

Types and formats: [DATA_DICTIONARY.md](./DATA_DICTIONARY.md).

## Methodology

- The files hold 1,000 rows of the 52,244 names in the live list today.
- Every row is a one-word domain name.
- Status and prices are the last ones Unique Domains stored for each name, not a reading taken on the day of the rebuild.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The snapshot is the day of the rebuild; each row's status is the last one stored, not a reading of that day.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique Domains, Expiring One-Word Domains, https://unique.domains/domains/expiring, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=related_tld_page)
- [.app](https://github.com/UniqueDomains/app-oneword-domains), [page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)
- [Short](https://github.com/UniqueDomains/short-oneword-domains)

Every ending Unique Domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=related_hub).

## About Unique Domains

[Unique Domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_expiring_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts, refreshed every night.

From code: the [Node.js SDK and CLI](https://github.com/UniqueDomains/nodejs) (`npm install @uniquedomains/sdk`), the [Python client](https://github.com/UniqueDomains/python) (`pip install uniquedomains`) and the [MCP server](https://github.com/UniqueDomains/mcp-server) for AI assistants, hosted at `https://mcp.unique.domains/mcp`.

Questions and corrections: `kai@unique.domains`
