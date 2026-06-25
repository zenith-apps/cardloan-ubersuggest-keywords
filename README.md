# Card Loan Ubersuggest Keywords

Ubersuggest keyword export for the Japanese seed keyword `カードローン`.

This repository was generated on K11 under `/srv/projects` using the existing `/srv/projects/ubersuggest-keywords` client, shared token cache, and shared rate-limit handling.

The export uses `lang=ja`, `country=jp`. It includes keyword, search volume, CPC, CPC dollars, SEO difficulty, paid difficulty, competition, search intent, update timestamp, and acquisition source metadata where Ubersuggest returned it.

## Files

- Download the volume-sorted CSV:
  `https://raw.githubusercontent.com/zenith-apps/cardloan-ubersuggest-keywords/main/data/cardloan_keywords_by_volume.csv`
- Download the adjacent seed candidates CSV:
  `https://raw.githubusercontent.com/zenith-apps/cardloan-ubersuggest-keywords/main/data/adjacent_seed_candidates_no_cardloan.csv`
- Download the card-loan provider candidates CSV:
  `https://raw.githubusercontent.com/zenith-apps/cardloan-ubersuggest-keywords/main/data/cardloan_provider_candidates.csv`
- Download the card-loan product catalog CSV:
  `https://raw.githubusercontent.com/zenith-apps/cardloan-ubersuggest-keywords/main/data/cardloan_product_catalog.csv`

- `data/cardloan_keywords_enriched.csv` - main CSV export.
- `data/cardloan_keywords_enriched.json` - same rows in JSON.
- `data/cardloan_keywords_by_volume.csv` - all current keywords sorted by search volume descending.
- `data/cardloan_keywords_by_volume.json` - JSON version of the volume-sorted export.
- `data/adjacent_seed_candidates_no_cardloan.csv` - adjacent seed candidates that do not include `カードローン`.
- `data/adjacent_seed_candidates_no_cardloan.json` - JSON version of the adjacent seed candidates.
- `data/cardloan_provider_candidates.csv` - card-loan provider/company candidates aggregated by provider.
- `data/cardloan_provider_candidates.json` - JSON version of the provider candidate list.
- `data/cardloan_product_catalog.csv` - product-level card-loan catalog used to expand the provider list.
- `data/cardloan_product_catalog.json` - JSON version of the product catalog.
- `data/cardloan_provider_collection_sources.json` - source pages and counts for the provider/product expansion.
- `data/cardloan_keywords_match_all.csv` - all keywords from paged `match_keywords` before enrichment.
- `data/cardloan_keywords_match_all.json` - JSON version of the paged match export.
- `data/cardloan_keywords_missing_after_enrichment.csv` - keywords that still lacked metrics after enrichment, if any.
- `raw/raw_match_pages.jsonl` - raw paged `match_keywords` responses.
- `raw/progress.log` - acquisition progress and rate-limit/split events.
- `summary.json` - run summary and counts.

Raw keyword data is committed here by explicit user instruction for this run. Secrets, cookies, Chrome profiles, and token caches are not included.
