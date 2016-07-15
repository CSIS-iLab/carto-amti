# Carto-AMTI

Multilayer maps app for use in AMTI's maritime geotracking.

### Documentation

1. https://docs.cartodb.com/cartodb-platform/cartodb-js/api-methods/
2. https://carto.com/blog/multilayer-geoportal/

### Notes/Bugs/Future Improvements

- New Carto API has difficulty rendering in-map drawn legends, had to create separate html files with handcoded `<ul>` elements:
  - `features_multilayer.html`: https://amti.csis.org/arbitration-map/
  - `islands_multilayer.html`: https://amti.csis.org/scs-features-map/
  - `claims_multilayer.html`: https://amti.csis.org/maritime-claims-map/
  - `disputes_multilayer.html`: https://amti.csis.org/disputes-map/
- Can Carto API handle more advanced SQL queries to consolidate total number of Google Sheets controlling source data?
- Investigate performance/loadability improvements.
- Improve mobile resizing.
- Add separate languages filter.
