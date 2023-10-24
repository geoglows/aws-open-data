# Changelog for s3://geoglows-v2

A list of modifications made to the `GEOGloWS Hydrologic Model V2` S3 buckets sponsored by the AWS Open Data Program. Changes listed in reverse chronological order. Approximate dates and times given in UTC.

- s3://geoglows-v2/CHANGELOG.md
- Region: us-west-2
- http://geoglows-v2.s3-website-us-west-2.amazonaws.com/

## 2023-10-24

1. Add license.md which contains the licensing statement for GEOGloWS V2 and all licenses and statements required by the open source data and software used by GEOGloWS V2.

## 2023-10-23

1. Replaced all geopackages in `/streams` with exact copies but with the coordinate reference properly set in the metadata. All files are (and were) in EPSG:4326 but were not correctly recognized by GIS software.

2. Files renamed to follow the naming convention of all other files `{product}_{vpu}_{optional-details}.{extension}`. The stream files are now named `streams_{vpu}.gpkg`.
