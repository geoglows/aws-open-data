# Changelog for s3://geoglows-v2

A list of modifications made to the `GEOGloWS Hydrologic Model V2` S3 buckets sponsored by the AWS Open Data Program. Changes listed in reverse chronological order. Approximate dates and times given in UTC.

- s3://geoglows-v2/CHANGELOG.md
- Region: us-west-2
- http://geoglows-v2.s3-website-us-west-2.amazonaws.com/ 

## 2023-10-23
Replaced all geopackages in `/streams` with exact copies but with the coordinate reference properly set in the metadata. All files 
are (and were) in EPSG:4326 but were not correctly recognized by GIS software. Files follow the naming pattern 
vpu_<3-digit-vpu-number>_streams.gpkg.
