# Winter Weather Property Damage Analysis
Combining mapping analyses of county-level winter weather loss (SHELDUS), snowfall accumulation (NOHRSC), and different reanalysis weather variables (ERA5) to identify key drivers of Midwest DJF property damage.

![Total Midwest Property Damage](Outputs/SHELDUS/total_damage_map.png)

---

## Research Overview

This project investigates which parts of the U.S. Midwest are most vulnerable to winter 
weather hazards, and what large-scale atmospheric patterns drive the costliest events. 
The analysis combines county-level property damage records with upper-air reanalysis data 
to build a picture of both the *where* and the *why* of Midwest winter losses.

The work proceeds in three stages:

1. **Loss Analysis (SHELDUS):** County-level property damage from winter weather, wind, 
   hail, and severe storms across 12 Midwest states during December–February (DJF), 
   1995–2023. Damage is mapped spatially and analyzed as a time series, with ENSO phase 
   years highlighted to explore potential teleconnection signals.

2. **Snowfall Analysis (NOHRSC):** Event-level snowfall accumulation maps using NOHRSC 
   sfav2 24-hour snowfall data, visualized as cumulative totals, single-day maxima, 
   standard deviation, and days above a user-defined threshold.

3. **Atmospheric Diagnostics (ERA5):** Upper-air composite maps for high-damage event 
   dates, including:
   - Integrated Vapor Transport (IVT) and MSLP — moisture flux and surface pressure
   - Temperature and Geopotential Height — thermal structure and large-scale flow
   - Potential Vorticity and Geopotential Height — upper-level forcing and tropopause dynamics

The long-term goal is to overlay ERA5 composites onto the SHELDUS damage maps to identify 
recurring synoptic patterns behind the highest-loss events, and to assess whether those 
events were adequately warned — with implications for insurance and reinsurance loss modeling.
