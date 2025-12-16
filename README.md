# ImmigrstionRentBurdenNYC
Overview

This repository contains data, code, and documentation for an analysis of housing affordability among immigrant households in New York City, using 2024 American Community Survey (ACS) 1-Year Estimates.

The project examines whether areas with higher concentrations of foreign-born residents experience higher rent burden, defined as renter households spending 30% or more of household income on rent.

The analysis is descriptive and predictive, focusing on aggregate geographic patterns rather than individual-level causal inference.

Research Question

Do immigrant households in New York City spend a higher share of their income on rent than native-born households?

Data Sources

All data used in this repository come from publicly available U.S. Census Bureau sources:

American Community Survey (ACS) 2024, 1-Year Estimates

DP02 – Selected Social Characteristics

Share of foreign-born residents

DP04 – Selected Housing Characteristics

Rent burden indicators (≥30% of income spent on rent)

Geographic units depend on data availability (e.g., NYC aggregate, boroughs, or PUMAs).
Methods

The analysis proceeds in three main steps:

Data Cleaning & Descriptive Analysis

Extract foreign-born population share and rent burden indicators

Summarize citywide housing affordability patterns

Predictive Modeling

Linear regression with:

Dependent variable: Rent burden rate

Independent variable: Share of foreign-born residents

Optional controls (e.g., median income) when available

Interpretation

Results are interpreted as associational, not causal

Findings are compared with prior NYC housing and immigration research

Key Limitations

Uses aggregate ACS Data Profiles, not microdata

Analysis is ecological, not individual-level

ACS estimates are subject to sampling error, especially for smaller geographies
