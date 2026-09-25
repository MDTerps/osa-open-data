---
license: cc-by-4.0
pretty_name: Home Sauna Prices and Specs
language:
- en
tags:
- saunas
- prices
- product-specifications
size_categories:
- n<1K
configs:
- config_name: default
  data_files: saunacosts-catalog.csv
---

# Home Sauna Prices and Specs

The complete catalog behind SaunaCosts (https://saunacosts.com/), as one CSV file: 396 home saunas with their manufacturer specifications and, where we have one, the verified retail price range. It is the same data the site renders, exported by the same build. Free to use with attribution.

As of: prices verified 2026-09-24; export generated 2026-09-25. 324 of the 396 models carry a verified price range; the rest have blank price cells rather than estimates, which is the same rule the site follows. This copy is refreshed monthly from the site; the live file at https://saunacosts.com/data/ is always the newest.

## Files

- `saunacosts-catalog.csv`: 396 rows, 13 columns, exactly as served at https://saunacosts.com/data/
- `saunacosts-catalog.json`: the same rows as JSON records; a blank CSV cell is null here

## Fields

- `brand`
- `name`
- `product_type`
- `indoor_outdoor`
- `capacity_persons`
- `heater_kw`
- `power_requirements`
- `wood_type`
- `exterior_dimensions`
- `warranty_years_display`
- `price_low`: low end of the verified retail listings at the last re-check
- `price_high`: high end of the verified retail listings at the last re-check
- `source_page`: the model's page on SaunaCosts, where current listings and the re-check date are shown

## What is in it, and what is not

Columns cover the specifications we verify from manufacturer pages plus price_low and price_high, the range of verified retail listings per model at the last re-check. Blank cells mean we could not verify a value, never zero. The export deliberately excludes per-merchant listings and links; those live on the item pages.

## License

Creative Commons Attribution 4.0 (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/

Use this data for anything, including commercial work, on one condition: attribute it to SaunaCosts with a link to https://saunacosts.com/ wherever the data or work built from it appears.

## Source

- Source page: https://saunacosts.com/data/
- Methodology: https://saunacosts.com/methodology/
- Publisher: SaunaCosts, https://saunacosts.com/
