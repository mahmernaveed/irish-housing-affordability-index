# Constructing a Composite Housing Affordability Index for Irish Regions

**Research Question:**
Can a composite housing affordability index be constructed using income, rent,
and property price data across Irish regions?

**Student:** Muhammad Ahmer Naveed | ID: 24155080
**Subject:** Open Data Workflow
**Data Year:** 2022 — All 26 Irish Counties
**DOI:** [10.5281/zenodo.19615497](https://doi.org/10.5281/zenodo.19615497)

---

## Project Overview

This project builds a Composite Housing Affordability Index for all 26 Irish
counties using three open government datasets from 2022. Two affordability
ratios are calculated per county — the Price-to-Income Ratio (PTI) and the
Rent-to-Income Ratio (RTI) — which are then normalised and averaged into a
single index score where 0 = most affordable and 1 = least affordable.

Key finding: Dublin is the least affordable county (index: 0.94) and Longford
is the most affordable (index: 0.03).

---

## Datasets Used

| Dataset | Description | Source |
|---|---|---|
| GPIIA01 | Median Gross Household Income by Electoral Division | CSO Ireland |
| RIQ02 | RTB Average Monthly Rent Report by County | Residential Tenancies Board |
| RPPR | Residential Property Price Register | PSRA / Gov.ie |

All datasets are for the year 2022 and are freely available from Irish
government open data portals.

---

## Repository Contents

| File | Description |
|---|---|
| `Household_Income.csv` | Raw CSO income data (GPIIA01) |
| `Property_Prices.csv` | Raw RPPR sale price data |
| `RTB_Rent_Report.csv` | Raw RTB rent data (RIQ02) |
| `affordability_index.ipynb` | Full Python notebook — cleaning, merging, analysis |
| `affordability_results.csv` | Final processed results for all 26 counties |
| `affordability_index.png` | Four-panel visualisation of results |

---

