# Unit-Hydrograph-Analysis
Computation of catchment area and unit hydrograph derivation using ERH and DRH data with least squares regression

This project focuses on hydrological analysis for a catchment using given **Excess Rainfall Hyetograph (ERH)** and **Direct Runoff Hydrograph (DRH)** data from a 3-hour storm event. The tasks involve computing the catchment area, deriving a unit hydrograph using least squares regression, and generating unit hydrographs for different storm durations.

## Problem Statement
Given:
- **ERH Data:** Rainfall intensity (mm/hour) at 0.5-hour intervals.
- **DRH Data:** Direct runoff flows (m³/sec) at 0.5-hour intervals.

Objectives:
1. **Catchment Area:** Compute using the ERH and DRH relationship.
2. **Unit Hydrograph:**  
   - Derive ordinates at 0.5-hour intervals using least squares regression.  
   - Determine the duration of the unit hydrograph.
3. **Duration Conversion:** Derive 75-minute and 90-minute unit hydrographs from the 0.5-hour unit hydrograph.

## Methods Used
- Rainfall-runoff relationship for catchment area estimation.
- Least squares regression for unit hydrograph derivation.
- S-curve method for changing unit hydrograph duration.
- Hydrograph plotting using Python/Matlab.

## Steps Performed
1. Tabulated ERH and DRH data.
2. Converted rainfall excess to runoff volumes.
3. Applied the least squares method to compute unit hydrograph ordinates.
4. Used the S-curve method to derive 75-min and 90-min unit hydrographs.
5. Plotted hydrographs for comparison.
