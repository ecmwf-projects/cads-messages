---
date: 2026-06-08T00:00:00Z
severity: warning
entries: derived-era5-single-levels-daily-statistics
live: true
---
An issue with the following parameters has been identified:

- `maximum_2m_temperature_since_previous_post_processing`
- `minimum_2m_temperature_since_previous_post_processing`
- `10m_wind_gust_since_previous_post_processing`
- `maximum_total_precipitation_rate_since_previous_post_processing`
- `minimum_total_precipitation_rate_since_previous_post_processing`

Please refer to the documented [Known issue](https://confluence.ecmwf.int/display/CKB/ERA5+family+post-processed+daily+statistics+documentation#ERA5familypostprocesseddailystatisticsdocumentation-KnownIssues) for details. **Data downloaded for the parameters listed above should not be used.** A fix is to be released as soon as possible. Please [follow updates on this topic on our Forum announcement](https://forum.ecmwf.int/t/issue-affecting-some-parameters-from-the-era5-post-processed-daily-statistics-on-single-levels/15057).
