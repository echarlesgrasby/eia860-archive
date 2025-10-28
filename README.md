# eia860-archive
This is intended to archive EIA-860 generator parameter files from the Energy Information Authority in support of my dissertation work. 

## Source

These files were initially sourced from this repository (publicly) available from the [EIA 860 Webpage](https://www.eia.gov/electricity/data/eia860/).
They are placed on the EIA website as .zip files. These were downloaded and extracted into flat folder layouts before uploading to this repository. 

## Processing

The spreadsheets that contain this data are dense and somewhat messy. My plan is to perform some conversions and stage these into a staging database in roughly the same "shape" as they exist currently (just without being contained in .xlsx files). I'll then develop a process to move this data into a legitimate warehouse format. This is to give the domain-specific langauge that I'm building in [_MERLIN_](https://merlinlang.xyz) a datasource that it can perform actions on.
