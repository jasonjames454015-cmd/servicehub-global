# Free Public Real Estate Data Research Checklist

**Version:** 0.2 Improved Draft  
**Date:** 2026-10-13  
**Use:** Educational / research only. Always verify current public access and comply with site terms. No scraping behind logins. No paid APIs.

## Pre-Flight
- [ ] Confirm you are using only free, publicly accessible sources (official .gov preferred).
- [ ] No paid API keys or accounts required for basic research.
- [ ] Document the source URL and access date for every data point.
- [ ] Respect robots.txt and terms; manual lookup only.

## Step 1: Identify Location
- [ ] Obtain full address or ZIP code.
- [ ] Use free Census Geocoder: https://geocoding.geo.census.gov/ (get county, FIPS, census tract, lat/long).
- [ ] Note jurisdiction details.

## Step 2: County Property Records (Assessor / Recorder)
Search for official portals. Examples of free public access:
- King County, WA: https://kingcounty.gov/en/dept/assessor/buildings-and-property/property-value-and-information/look-up-property-information (search by address or parcel).
- Maryland SDAT: https://sdat.dat.maryland.gov/RealProperty/Pages/default.aspx (statewide, select county).
- Many others: Search "[County Name] [State] assessor property search" or "property appraiser".
- Retrieve (if public): owner name, assessed value, tax amount, property type, square footage, sales history.
- Screenshot or note the official URL and date accessed. Avoid aggregator sites that require accounts for full data.

## Step 3: Census Demographics & Housing
- [ ] Go to data.census.gov.
- [ ] Search by census tract, county, or ZIP for ACS 5-year estimates: median household income, housing occupancy, median home value (e.g., tables DP04 Selected Housing Characteristics, B25077 Median Value).
- [ ] Record the ACS year (e.g., 2019-2023 or latest available).
- Free API available at api.census.gov (key free to register).

## Step 4: Flood & Hazard (Free)
- [ ] Use FEMA Flood Map Service Center: https://msc.fema.gov/portal/home (public viewer, address search).
- [ ] Determine flood zone for the address.
- [ ] Check state GIS portals if available (search "[State] GIS parcel viewer").

## Step 5: Additional Free Sources
- [ ] data.gov catalog for housing-related datasets.
- [ ] HUD User: https://www.huduser.gov/ (fair market rents, etc.).
- [ ] Local treasurer sites for tax delinquency status (official .gov).

## Step 6: Compile & Document
- [ ] Create a simple one-page summary with sources and dates.
- [ ] List all URLs accessed.
- [ ] Flag any data that required login or payment (do not use those).
- [ ] Note limitations: data varies by county; some require in-person requests.

## Notes
- Availability varies widely. Prioritize official government sites.
- This checklist is the foundation for a future digital product (PDF or Notion template). Currently free draft.
- No revenue generated from this draft. For sale only after real buyer interest and polish.

**Status:** Improved with specific free source links. Ready for further expansion or PDF conversion.  
**Next:** Add more county examples or convert to downloadable format.