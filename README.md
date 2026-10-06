# FIT3179_DV2

## Data preparation

### Station entries
Source: DataVic, Annual metropolitan train station patronage (FY2018-19 to FY2024-25)
Steps: combined yearly CSVs in Excel under one header; saved as data/station_entries.csv

### SA3 boundaries
Source: ABS ASGS 2016, SA3 shapefile
mapshaper commands:
-proj wgs84
-simplify 5% keep-shapes
-o format=topojson