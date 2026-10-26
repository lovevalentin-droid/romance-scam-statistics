# Romance Scam Statistics — Open Dataset (2024–2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23655737.svg)](https://doi.org/10.5281/zenodo.23655737)

Verified, source-attributed statistics on romance scams ("arnaques sentimentales"), compiled and fact-checked in June 2026 for the **Baromètre des arnaques sentimentales**. Every figure was verified against the primary report before inclusion; figures that could not be traced to a primary or clearly-attributed secondary source were excluded.

📊 Human-readable versions:
- 🇫🇷 [Baromètre 2026 des arnaques sentimentales](https://www.arnaques-rencontres.fr/fr/articles/statistiques-arnaques-sentimentales-france)
- 🇬🇧 [Romance scam statistics 2025-2026](https://www.arnaques-rencontres.fr/en/articles/romance-scam-statistics)

## Headline figures

| Metric | Value | Year | Source |
|---|---|---|---|
| US losses reported to FBI (confidence/romance) | $929,287,469 (+38% YoY) | 2025 | FBI IC3 2025 Internet Crime Report |
| US complaints (FBI IC3) | 23,159 (+29% YoY) | 2025 | FBI IC3 |
| US losses, victims aged 60+ | $584M — 63% of total (+50% YoY) | 2025 | FBI IC3 (Elder Fraud) |
| Romance losses with likely AI nexus | $19M (626 complaints) | 2025 | FBI IC3 (AI section) |
| Romance losses with crypto nexus | $394.8M — 42% of US total | 2025 | FBI IC3 |
| US losses reported to FTC | $1.49B, 70,588 reports (60,916 in 2024) | 2025 | FTC Consumer Sentinel interactive data |
| Most frequent transaction type in romance-scam losses | Prepaid/gift cards 31%, cryptocurrency 25%, wire 21% | 2025 | FBI IC3 (p. 10) |
| Romance scams starting on social media | ~60% of 2025 money-loss victims | 2025 | FTC press release, Apr 27, 2026 |
| UK losses (City of London Police) | £102M+, 10,784 reports (+29%) | 2025 | CoLP, May 5, 2026 |
| France: validated police reports | ≈3,400 | 2024 | DGPN via franceinfo |
| Average crypto-scam payment | $782 → $2,764 (+253%) | 2024→2025 | Chainalysis 2026 Crypto Crime Report |
| Adults worldwide who encountered a scam (12 mo) | 57% (23% lost money) | 2025 | GASA Global State of Scams 2025 |

Full machine-readable data with source URLs and exact citations: [`data/romance-scam-statistics.json`](data/romance-scam-statistics.json)

## Practical guides for people targeted (French)

- [Comment reconnaître un brouteur](https://www.arnaques-rencontres.fr/fr/articles/brouteur-guide-complet): definition, methods and the 12 signs of a "brouteur" (West African romance scammer).
- [Victime d'une arnaque sentimentale : que faire](https://www.arnaques-rencontres.fr/fr/articles/victime-arnaque-sentimentale-que-faire): the 7 steps to take, from cutting contact and alerting the bank to filing a police report and getting support.

## Changelog

- **2026.10 (October 26, 2026).** Corrected the transaction-type figure: in the FBI IC3 2025 report, prepaid and gift cards are the most frequently reported transaction type in confidence/romance losses (31%), ahead of cryptocurrency (25%); version 2026.06 wrongly gave cryptocurrency as first at 31%. FTC 2025 figures now cover the full year ($1.49B, 70,588 reports) instead of the first nine months.
- **2026.06 (June 12, 2026).** First release.

## Known data gaps

- France publishes **no official national financial total** for romance scams (volumes only).
- No EU-wide aggregate exists (Europol publishes qualitative analysis only).
- No recent primary study quantifies the under-reporting rate — widely-quoted ratios ("1 in 15–20 victims report") could not be traced to a primary source and are excluded.

## License & citation

Data compiled from public official sources. Reuse freely with attribution:

> Le Normand, V. (2026). *Romance Scam Statistics 2024-2026 (Baromètre 2026 des arnaques sentimentales)* [Data set]. Version 2026.10. Zenodo. https://doi.org/10.5281/zenodo.23655737

Permanent archive with DOI: https://zenodo.org/record/23655737 (concept DOI for all versions: 10.5281/zenodo.22284079).

Maintained by [Valentin Le Normand](https://www.valentin.love) — founder of an international matchmaking agency and editor of [arnaques-rencontres.fr](https://www.arnaques-rencontres.fr), a French romance-scam prevention site.
