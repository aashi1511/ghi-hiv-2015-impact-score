# ghi-hiv-2015-impact-score
HIV 2015 Impact Score calculation using the ORS dataset for the GHI Data Team skills task.
# HIV 2015 Impact Score – GHI Data Team Skills Task

This repository contains my submission for the Global Health Impact (GHI) Data Team skills task.

## Objective
The goal of this task is to compute country-level HIV treatment Impact Scores for the HIV 2015 ORS dataset using Python, following the methodology described in the provided model reference and the HIV 2013 example notebook.

## Methodology Overview
- Load the HIV 2015 ORS dataset
- Clean and normalize multi-row headers
- Identify drug-specific impact columns
- Convert impact values to numeric format
- Compute the overall treatment impact score per country by summing drug-level impacts
- Perform a sanity check against ORS-provided totals (where available)
- Export final results to CSV

## Repository Contents
- `data/HIV2015_ORS.csv`  
  Raw HIV 2015 ORS dataset

- `notebooks/HIV_2015_impact_score.ipynb`  
  Python notebook implementing the impact score computation for HIV 2015

- `notebooks/HIV_2013_entity_map.ipynb`  
  Reference notebook used to understand the entity mapping and workflow

- `output/impact_score.csv`  
  Final computed HIV 2015 impact scores by country

- `Entity_Map (ReadME).md`  
  Process guide provided with the task

- `tmi13706-sup-0001-supinfo.docx.pdf`  
  Model reference document describing the impact score calculations

## Notes
Minor numerical differences between computed and ORS-provided impact values may occur due to floating-point precision.
