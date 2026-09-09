# Lab 03 data

This directory contains the course-provided oceanographic data used in Lab 03. It is a subset of the California Cooperative Oceanic Fisheries Investigations (CalCOFI) bottle database, prepared for the course and copied from the pinned source revision [`7c384a2048b5521314357ab18f538701947dee32`](https://github.com/rhodes-byu/stat-486/tree/7c384a2048b5521314357ab18f538701947dee32/data/OceanicFisheries).

| File | Purpose | Rows | SHA-256 |
| --- | --- | ---: | --- |
| `ocean_data.csv` | Training data, including the `T_degC` water-temperature target | 7,106 | `ba66b92e2715f9e64cbfe122bdb79c957d2f533bf46ce39736962817065b2bcb` |
| `ocean_data_newvalues.csv` | New observations without `T_degC`, used to verify the submitted model | 1,777 | `d910bcd002840e524a0a406ea4cd6d41766dc1c015ac7b0bfa2e76a556ca5b5e` |

The four categorical predictors are `Wea`, `Cloud_Typ`, `Cloud_Amt`, and `Visibility`; all remaining non-target columns are numeric predictors. Do not alter either CSV file.
