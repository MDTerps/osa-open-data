---
license: cc-by-4.0
pretty_name: Home EV Charger Prices and Specs
language:
- en
tags:
- ev-chargers
- prices
- product-specifications
size_categories:
- n<1K
configs:
- config_name: default
  data_files: evchargerindex-catalog.csv
---

# Home EV Charger Prices and Specs

The complete catalog behind EV Charger Index (https://evchargerindex.com/), as one CSV file: 246 home EV chargers with their manufacturer specifications and, where we have one, the verified retail price range. It is the same data the site renders, exported by the same build. Free to use with attribution.

As of: prices verified 2026-09-24; export generated 2026-09-25. 175 of the 246 models carry a verified price range; the rest have blank price cells rather than estimates, which is the same rule the site follows. This copy is refreshed monthly from the site; the live file at https://evchargerindex.com/data/ is always the newest.

## Files

- `evchargerindex-catalog.csv`: 246 rows, 18 columns, exactly as served at https://evchargerindex.com/data/
- `evchargerindex-catalog.json`: the same rows as JSON records; a blank CSV cell is null here

## Fields

- `brand`
- `name`
- `model_number`
- `product_type`
- `form_factor`
- `output_power_kw`
- `output_current_a`
- `input_voltage_v`
- `connector`
- `plug`
- `cable_length_ft`
- `es_certified`
- `safety_listing`
- `enclosure`
- `warranty`
- `price_low`: low end of the verified retail listings at the last re-check
- `price_high`: high end of the verified retail listings at the last re-check
- `source_page`: the model's page on EV Charger Index, where current listings and the re-check date are shown

## What is in it, and what is not

Columns cover the specifications we verify from manufacturer pages plus price_low and price_high, the range of verified retail listings per model at the last re-check. Blank cells mean we could not verify a value, never zero. The export deliberately excludes per-merchant listings and links; those live on the item pages.

## License

Creative Commons Attribution 4.0 (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/

Use this data for anything, including commercial work, on one condition: attribute it to EV Charger Index with a link to https://evchargerindex.com/ wherever the data or work built from it appears.

## Source

- Source page: https://evchargerindex.com/data/
- Methodology: https://evchargerindex.com/methodology/
- Publisher: EV Charger Index, https://evchargerindex.com/
