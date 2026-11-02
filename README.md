# Predicting Low-Carbon Hours for Data-Center Computing

AC209A — Fall 2026  
**Project group:** 14
**Team members:** Minh-Thy Tyler, Gabe Gonzalez, Noah Schiro

## Project Overview

**Research Question:** Can we predict the lowest-carbon hours of the electricity grid one day in advance accurately enough to reduce estimated emissions from flexible data-center workloads?

We plan to use hourly electricity data for the PJM balancing authority to estimate and predict grid carbon intensity. We will then simulate scheduling a flexible computing workload during predicted lower-carbon hours and compare its estimated emissions with an immediate-start schedule and an ideal schedule based on observed carbon intensity.

## Data

Our primary source is the **U.S. Energy Information Administration’s EIA-930 dataset**, which includes hourly electricity demand, demand forecasts, generation by energy source, and electricity exchanges between balancing authorities.

- **Electricity data:** [Add source/download link]
- **Emissions factors:** [Add verified source and units]
- **Study period:** [Start date–end date]
- **Unit of observation:** One hour in the PJM balancing authority
- **Cleaned dataset dimensions:** [Rows × columns]

Weather data may be added if suitable predictors available at prediction time can be obtained.

### Carbon Intensity Calculation

Before calculating carbon intensity, we will verify that electricity-generation data and emissions factors use compatible units. Fuel-based emissions factors cannot be applied directly to electricity generation without an appropriate conversion. We will also document how electricity imports and exports are handled and whether our target represents production-based or consumption-based carbon intensity.

