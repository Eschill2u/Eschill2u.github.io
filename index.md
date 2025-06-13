---
title: Emma Schillerstrom
---

## Presentations (Quarto revealjs)

#### Reproducible Workflows in R [(View GitHub)](https://github.com/USFWS/data-workflow-presentation)

#### Introduction to Quarto [(View GitHub)](https://github.com/USFWS/intro-to-quarto)

## Apps/Dashboards

#### ServCat Dashboard for Refuge Managers
An R Shiny application that 
- monitors the progress of "Operation ServCat", a USWFS Region 7 (Alaska) project intiated to preserve historic National Wildlife Refuge (NWR) documents, allowing NWR staff to track whether their goals are being met for making their refuges information secure, accessible, discoverable, and documented
- integrates data from ServCat, the USFWS national repository for data and documents, via API
- summarizes and visualizes information for a selected refuge
presented at 2023 national Inventory and Monitoring data manager meeting

#### ServCat Dashboard for Regional Office
An R Shiny application that
-  monitors the progress of "Operation ServCat", allowing Division of Natural Resouces staff to track whether regional data management progress goals are being met
-  integrates data from ServCat via API
-  summarizes and visualizes information related to partner contributions, rate of preservation, and progress over time
presented at 2023 national Inventory and Monitoring data manager meeting

#### Survey Product Preservation Monitoring App [(View GitHub)](https://github.com/USFWS/check-survey-preservation)
A cross-regional R Shiny application that
- produces summary reports of survey product preservation
- generates data asset inventory Excel workbooks with custom dropdown lists and auto-filled data from FWS databases
(presented nationally with multiple regions expressing interest in adoption)

## National Wildlife Refuge (NWR) Data Workflows

#### Teltin NWR Wood Bison (*Bison bison athabascae*) Reintroduction Habitat Assessment
R scripts with reusable functions to
- compile and tidy large batches of individual snow probe data directly from third-party Propagation Labs Snow Scope app exports
- plot individual snow hardness depth profiles in kPa or on a log-adjusted Hand Hardness scale
- plot averaged (with error bands) snow hardness depth profiles for pooled plots or sites

#### Tetlin NWR Snowshoe Hare (*Lepus americanus*) Monitoring Survey
Reusable R scripts to 
- compile, tidy, and generate summary tables for all 33 years of historic hare pellet data
- calculate hare densities from pellet counts
- visualize the population cycle via a density time series plot

#### Tetlin NWR Trumpeter Swan (*Cygnus buccinator*) Census Survey
R Quarto report to
- isolate Tetlin NWR historic data from Migratory Bird Program statewide survey dataset
- compile and tidy newly-collected data with the 30 years of historic data
- perform exploratory data analysis, providing summary tables, correlation matrices, and plots visualizing abundance and productivity information
- compare summary metrics (total swans, breeding adults, total cygnets, annual growth rate, proportion breeding, average brood size) between datasets subsetted by percent volume contours, flightpath buffers, or a waterfowl polygon feature layer in order to determine a reasonable method for ensuring comparable spatial coverage between new and old data
- provide a reproducible, automated summary blurb with inline code calculations
- annotate code blocks in a human-readable language for all steps taken above

#### Kenai NWR Trumpeter Swan (*Cygnus buccinator*) Monitoring Survey
R scripts to 
- compile and tidy 67 years of data
- QC and correct a few inconsistencies in the compiled data
- derive fields for survey type, number observations with matching coordinates within the same survey period (to identify changes in procedure over time), and spatially joined lake attribute data pertaining to aircraft landability and rules

R Quarto report with
-clear documentation of steps taken and modifications made to the raw dataset
-reproducible tables, plots, maps, images, and summaries exploring abundance and productivity over time, method consistency over time, spatial coverage consistency over time, outlier and duplicate observations to be reviewed for filtering, open versus closed lake usage, and considerations for lake occupancy analysis

#### Kenai NWR Fire Impacts to Dall Sheep (*Ovis dalli dalli*) Research Project
R Quarto report series (broken up 4 into parts) to
- provide introductory training to tidy data and R tidyverse
- walk through coding steps (via human-readable annotations) required to explore and tidy sheep fecal parasite data directly from the fecal flotation results provided by the labratory
- visualize data with plots showing parasite load by species and comparing parasite presence between sheep grazing in burned versus unburned areas
- visualize data with embedded, dynamic leaflet maps displaying parasite load relative to wildfire burn sites
- provide instructions detailing how to run and reuse the code and functions

#### Yukon Delta NWR Mark-Recapture Rotary Screw Trap Juvenile Salmon (*Oncorhynchus*) Monitoring Survey
Reusable R scripts to
- tidy entered data
- automate filling out the state Aquatic Resources Permit (ARP) [reporting form,](https://www.adfg.alaska.gov/index.cfm?adfg=otherlicense.aquatic_reports) eliminating weeks of manual data entry for over 43,000 fish by staff in 2024 and any time spent on this task in future years

#### *IN PROGRESS* Alaska Peninsula/Becharof NWR Willow Ptarmigan (*Lagopus lagopus*) Monitoring Survey
R scripts to 
- compile and tidy 3 years of distance sampling data

Reusable R code to 
- export an eBird checklist with ptarmigan and incidental bird observation data
- calculate bird perpendicular distances and estimated observer path lengths from bearing, observer waypoint, and rangefinder data
- for any given year, given a set of covariates, generate all possible models (to be replaced by *a priori* model list), fit detection functions, calculate bird densities, and generate an AIC table
- *COMING SOON* generate a fully automated, preservation-ready refuge report for any given year

## Other Languages (Python, Bash)

#### DFP Bioinformatics Project: Black Carp Genome Assembly Pipeline
2 Bash scripts and 1 Python script to
- something and compare three genome assemblers

#### *IN PROGRESS* Streamlining Document Selection for Preservation
Python script to
- streamline the initial process for preserving large (>100,000) batches of historic digital files by automating parsing through file directories, eliminating empty folders, and selecting and organizing the files by file types identified as appropriate for repository preservation
