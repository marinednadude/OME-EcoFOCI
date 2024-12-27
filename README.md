# OME-EcoFOCI

## Analysis of EcoFOCI eDNA Data

This folder includes data and analysis for organizing, conducting quality control/quality assurance (QA/QC), and merging environmental and sample data from PMEL OME EcoFOCI and affiliated Alaska & Arctic cruises.

Please see the OME [EcoFOCI Cruise Sample, Cast, Bottle Tracking & Merge Sheet](https://docs.google.com/spreadsheets/d/11QXcTJfCQOJlr_T2jyY2oBkj-a28jI5exChKEJYtuzg/edit?gid=0#gid=0) to link to google drive.
**GitHub is version controlled and records who made edits and what they are. The drive may be out of date. Refer to this as the most up to date source unless otherwise noted.**

**As of 12/27/2024 there are still missing environmental data.**

### Points of Contact
Shaun Bell is the main POC for EcoFOCI cruise data
Natalie Monacci is the main POC for RC0083 cruise data
Jackie Grebmeier at UMCES is the main POC for 2020_Oct_Norseman cruise data
Sean McAllister is the main POC for OME sample metadata
Zack Gold is the main POC for the R code

## Respository Contents
**arctic_data_merge_20241224.Rmd**
This file merges the output FinalOME_Merge_[CruiseShortCode].csv files and selects the appropriate metadata and sample data to be fed into REVAMP: *run1_4_revamp_formatted_metadata.csv*

**data\1_SampleCollection** directory contains all metadata and sampledata for each cruise. Each cruise has its own folder.
Each should contain:

- Archive electronic sample metadata sheet
- Machine Readible Electronic Sample Metadata Sheet
- QAQCMRE_CruiseSampleMetadata_shortcruiseCode	
- Raw Bottle File	(not all cruises have bottle files yet, particularly mooring deployments)
- QA/QC Downcast File (not all cruises have raw downcast files that EcoFOCI typically uses for environmental analyses)
- FinalOME_Merge_shortCruiseCode
- Output FinalOME_Merge_shortCruiseCode



