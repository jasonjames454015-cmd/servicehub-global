# Real Estate Research Notes (Compliance-First, Free Sources Only)

**Rule:** Use only freely accessible public data. No paid APIs, no login-walled sites, no scraping that violates terms.

## Primary Free Sources

### 1. County Assessor & Recorder Offices
- Property ownership, assessed values, tax history, sales records (where public).
- Access: Most counties have free online search portals on official .gov sites.
- Start: Search "[County Name] [State] property search" or "assessor".

### 2. U.S. Census Bureau
- American Community Survey (ACS): demographics, housing occupancy, median income, home values by tract.
- American Housing Survey.
- Access: data.census.gov (free).

### 3. Federal Portals
- data.gov: searchable catalog of government datasets.
- HUD: fair market rents, assisted housing data (huduser.gov).
- FEMA: National Flood Hazard Layer (public map viewer).

### 4. State & Local GIS
- Many states/counties offer free GIS viewers or downloadable parcel data.

## Workflow Example (ZIP or Address Research)
1. Geocode address → county/FIPS (use free Census geocoder or OpenStreetMap).
2. Pull assessor record for ownership/tax.
3. Overlay Census tract demographics.
4. Check FEMA flood zone.
5. Note any public sales history.

## Potential Productization
Turn the above into a downloadable checklist or template for investors/researchers. Sell as digital product once polished. All based on public info.

**Status:** Research notes only. No data downloaded or tools built yet.