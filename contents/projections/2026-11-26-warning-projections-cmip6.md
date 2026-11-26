---
date: 2026-11-26T00:00:00Z
severity: warning
entries: projections-cmip6
live: true
---
In the coming months, the CMIP6 dataset will be updated. The update will:

- mirror changes at ESGF (data that has been retracted or updated);
- add new data that meets the selection criteria;
- fix known inconsistencies, such as missing historical and scenario data.

**Once the update is live (and not before)**, some combinations of model, experiment, variable or period that are available today will be removed or replaced with the latest version, and new ones will be added. API requests that use a removed combination will stop working after the update. If you use scripts or automated workflows, please check your requests against the download form once the update is live and adjust them where needed.
