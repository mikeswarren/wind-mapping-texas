# Texas Wind Energy & Wind-Speed Spatial Analysis

Statewide interpolation of near-surface wind speed vs. operating wind-turbine locations
(wind power scales with v³).

- **Data:** ASOS METAR observations, 226 stations (Iowa State portal), QA-reduced to ~5,967
  records / per-station monthly means (March 2019).
- **Method:** Inverse Distance Weighting (IDW) surface; 3-D visualization in ArcScene over a
  30 m DEM; turbines from the USGS/LBNL/AWEA U.S. Wind Turbine Database.
- **Stack:** ArcGIS · IDW interpolation · METAR/ASOS

_Advanced GIS, Old Dominion University. Portfolio project by [Michael Warren](https://mikeswarren.com)._
