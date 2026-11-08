# Free Public Real Estate Data Research Checklist

**Version:** 0.9 Polished Draft  
**Date:** 2026-11-07  
**Use:** Educational / research only. Always verify current public access and comply with site terms. Manual lookup preferred. No scraping behind logins. No paid APIs.

## Pre-Flight
- [ ] Confirm you are using only free, publicly accessible sources (official .gov preferred).
- [ ] No paid API keys or accounts required for basic research.
- [ ] Document the source URL and access date for every data point.
- [ ] Respect robots.txt and terms of use.
- [ ] Note data freshness (assessor data often lags; Census is multi-year estimates).

## Step 1: Identify Location
- [ ] Obtain full address or ZIP code.
- [ ] Use free Census Geocoder: https://geocoding.geo.census.gov/geocoder/geographies/address (get county, FIPS, census tract, lat/long).
- [ ] Note jurisdiction details (county, state, city).

## Step 2: County Property Records (Assessor / Recorder)
Search for official portals. Examples of free public access (verified as .gov):
- King County, WA: https://kingcounty.gov/en/dept/assessor/buildings-and-property/property-value-and-information/look-up-property-information
- Maryland SDAT (statewide): https://sdat.dat.maryland.gov/RealProperty/Pages/default.aspx
- Los Angeles County, CA: https://assessor.lacounty.gov/ (Property Search)
- Cook County, IL: https://www.cookcountyassessor.com/ (search portal)
- Many others: Search "[County Name] [State] assessor property search" or "property appraiser".
- Retrieve (if public): owner name (where allowed), assessed value, tax amount, property type, square footage, year built, last sale date/price (varies by state).
- Screenshot or note the official URL and date accessed. Prefer direct .gov over third-party aggregators.

## Step 3: Census Demographics & Housing
- [ ] Go to https://data.census.gov
- [ ] Search by census tract, county, or ZIP for ACS 5-year estimates: median household income, housing occupancy, median home value, housing units (tables like DP04, B25077, S2503).
- [ ] Record the ACS year (e.g., 2019-2023 or latest available).
- Free API at https://api.census.gov (optional free key registration).

## Step 4: Flood & Hazard (Free)
- [ ] Use FEMA Flood Map Service Center: https://msc.fema.gov/portal/home (public viewer, address search).
- [ ] Determine flood zone for the address.
- [ ] Check state GIS portals (search "[State] GIS parcel viewer" or open data portal).

## Step 5: Additional Free Sources
- [ ] data.gov: search "housing", "real property", "parcel".
- [ ] HUD User: https://www.huduser.gov/ (Fair Market Rents, housing data). FY2026 FMRs available free.
- [ ] FHFA House Price Index: https://www.fhfa.gov/data (downloadable HPI).
- [ ] Freddie Mac PMMS (educational rates only): https://www.freddiemac.com/pmms — as of 2026-11-05: 30-year fixed 7.18% (down 0.06 from prior week), 15-year 6.57% (down 0.03). Not a quote; check latest Thursday release. Source: freddiemac.com/pmms. Next expected 2026-11-12.
- [ ] USGS Authoritative Source Parcel Viewer (index of free parcel publishers): useful starting point to find county portals.  
- [ ] OpenFEMA datasets (public, no login): https://www.fema.gov/about/openfema/data-sets — housing assistance, NFIP, disaster data.
- [ ] Local treasurer/tax collector sites for tax status (official .gov).
- [ ] OpenAddresses for address validation: https://openaddresses.io

## Step 6: Compile & Document
- [ ] Create a simple one-page summary with sources, dates, and key findings.
- [ ] List all URLs accessed.
- [ ] Flag any data that required login or payment (do not use those for this research).
- [ ] Note limitations: data varies by county/state; some records require in-person or formal requests; always cross-verify.

## Notes
- Availability varies widely by jurisdiction. Prioritize official government sites.
- This checklist is a free draft foundation for a potential digital product (PDF, Notion template, or worksheet). Currently free.
- No revenue generated. For any future sale only after real buyer interest and further polish.
- Compliance: Public records only. Do not redistribute raw data in violation of source terms.

**Status:** v0.9 — Updated PMMS educational note to current rates as of 2026-11-05 (30yr 7.18%, 15yr 6.57%). Free PDF version regenerated on 2026-11-08.  
**Next:** Convert to simple PDF or add worksheet template.