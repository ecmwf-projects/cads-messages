---
date: 2026-10-21T00:00:00Z
severity: warning
entries: satellite-soil-moisture
live: true
---
The data for 1–20 September 2026 under v202505 (and v202505.1 for root-zone soil moisture) have many missing values in the PASSIVE, COMBINED, root-zone and Freeze/Thaw products and should not be used. API users should change 'version': 'v202505' (or 'v202505_1') to 'version': 'v202505_2' in their requests for dates from 1 September 2026. Please see 'Known Issues' in the Documentation tab and the [ECMWF Forum post](https://forum.ecmwf.int/t/delayed-update-of-soil-moisture-gridded-data-following-issue-identification/15456) for more information.
