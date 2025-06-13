---
title: Emma Schillerstrom
---

## Technical Presentations (Quarto revealjs)

#### Reproducible Workflows in R [(View GitHub)](https://github.com/USFWS/data-workflow-presentation)

#### Introduction to Quarto [(View GitHub)](https://github.com/USFWS/intro-to-quarto)

## Apps/Dashboards

#### ServCat Dashboard for USFWS Region 7 National Wildlife Refuge Managers [(View GitHub)](https://github.com/USFWS/r7-opservcat-refuge-dashboard)
*presented nationally at 2023 Inventory and Monitoring data manager meeting*

An R Shiny application that 
- monitors the progress of "Operation ServCat", a regional project intiated to preserve historic National Wildlife Refuge program documents, allowing NWR staff to track whether their goals are being met for making their refuge's information secure, accessible, discoverable, and documented
- interactively integrates data from ServCat, the USFWS national repository for data and documents, via API, summarizing and visualizing information for a selected refuge

#### ServCat Dashboard for USFWS Region 7 Regional Office [(View GitHub)](https://github.com/USFWS/r7-opservcat-management-dashboard)
*presented nationally at 2023 Inventory and Monitoring data manager meeting*

An R Shiny application that
-  monitors the progress of "Operation ServCat", allowing Division of Natural Resouces staff to track whether regional data management progress goals are being met
-  integrates data from ServCat via API, summarizing and visualizing information related to partner contributions, rate of preservation, and progress over time among refuge stations (regionally) and regions (nationally)

#### Survey Product Preservation Monitoring App [(View GitHub)](https://github.com/USFWS/check-survey-preservation)
*presented nationally at 2024 Inventory and Monitoring data manager meeting*

A cross-regional R Shiny application that
- integrates data from ServCat and PRIMR, the USFWS national NWR survey management database, via API
- produces summary reports of data assets preserved for each wildlife survey pertaining to a selected region, refuge, and/or survey coordinator
- generates downloadable data asset inventory Excel workbooks with custom dropdown lists and auto-filled data from the ServCat database for use in succession planning

#### Pilot Study for Using PRIMR data for Survey Review and Planning
*presented nationally at 2024 Inventory and Monitoring data manager meeting*

A Quarto report that
- details the utilities and limitations of using PRIMR for reviewing survey accomplishments and conducting work planning, such as selecting and prioritizing surveys for data collection, using Tetlin NWR as a test case
- is being used to inform a replacement database for PRIMR

An accompanying R Shiny application that
- uses PRIMR data to predict expected surveys to be conducted during the current year
- generates a reactive checklist table of all surveys at a refuge with priortization information for each survey, including time required, cost, survey timing, coordinator, Inventory and Monitoring Plan ranked prioty level, whether or not it is cooperative, and whether or not it pertains to priority resources of concern (pROCs)
- updates summary info (e.g., time per coordinator, total time and monetary costs, number of surveys) for the field season, depending on which surveys are selected in the checklist table

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
- clear documentation of steps taken and modifications made to the raw dataset
- reproducible tables, plots, maps, images, and summaries exploring abundance and productivity over time, method consistency over time, spatial coverage consistency over time, outlier and duplicate observations to be reviewed for filtering, open versus closed lake usage, and considerations for lake occupancy analysis

#### Kenai NWR Fire Impacts to Dall Sheep (*Ovis dalli dalli*) Research Project
R Quarto report series (broken up into 4 parts) to
- provide introductory training to tidy data and R tidyverse
- walk through coding steps (via human-readable annotations) required to explore and tidy sheep fecal parasite data directly from the fecal flotation results provided by the labratory
- visualize data with plots showing parasite load by species and comparing parasite presence between sheep grazing in burned versus unburned areas
- visualize data with embedded, dynamic leaflet maps displaying parasite load relative to wildfire burn sites
- provide instructions detailing how to run and reuse the code and functions

#### Yukon Delta NWR Mark-Recapture Rotary Screw Trap Juvenile Salmon (*Oncorhynchus*) Monitoring Survey
Reusable R scripts to
- tidy entered data
- automate filling out the state Aquatic Resources Permit (ARP) [reporting form,](https://www.adfg.alaska.gov/index.cfm?adfg=otherlicense.aquatic_reports) eliminating weeks of manual data entry for over 43,000 fish by staff in 2024 and any time spent on this task in future years

#### Alaska Peninsula/Becharof NWR Willow Ptarmigan (*Lagopus lagopus*) Monitoring Survey (*In Progress*)
R scripts to 
- compile and tidy 3 years of distance sampling data

Reusable R functions to 
- export an eBird checklist with ptarmigan and incidental bird observation data
- calculate bird perpendicular distances and estimated observer path lengths from bearing, observer waypoint, and rangefinder data
- for any given year, given a set of covariates, generate all possible models (to be replaced by *a priori* model list), fit detection functions, calculate bird densities, and generate an AIC table with weights
- *COMING SOON* generate a fully automated, preservation-ready refuge report for any given year

## Other Languages (Python, Bash)

#### DFP Bioinformatics Project: Black Carp Genome Assembly Pipeline
Resuable 3-script (2 Bash (1 SLURM job script, 1 shell script), 1 Python) pipeline to
- convert raw PacBio sequencing reads to HiFi reads using circular consensus sequencing
- generate a quality report for the HiFi reads
- run three genome assemblers
- calculate and generate a table comparing various assembly metrics for all three assemblies in order to assess the success of each assembler with regard to contiguity, correctness, completeness, and computation

#### Streamlining Document Selection for Preservation (*In Progress*)
Reusable Python script to
- streamline the initial process for preserving large (>100,000) batches of historic digital files by automating parsing through file directories, eliminating empty folders, and selecting and organizing the files by file types identified as appropriate for repository preservation

## Research Posters and Presentations

#### Undergraduate Senior Research Honors Thesis Poster (2022)
<a href="docs/assets/undergrad_senior_thesis_2022.pdf" download>Physiological Impacts of Heavy Metals in the Blood of Blacktip Sharks (*Carcharhinus limabtus*) in Biscayne Bay, Florida</a>

#### USFWS Directorate Fellows Program (DFP) Final Presentation (2021)
<a href="docs/assets/dfp_2021.pdf" download>Genome Assembly for Invasive Black Carp (*Mylopharyngodon piceus*) Biocontrol</a>

#### High School Senior Thesis Poster (2017)
<a href="docs/assets/highschool_senior_thesis_2018.pdf" download>Analysis of Deceased *Limulus polyphemus* to Find Causes of Mortality on Wallops Island</a>

#### Biotechnology Research Internship Poster (2016)
<a href="docs/assets/ibbr_2016.pdf" download>Expression and Purification of Human IL-7 to Study its Immunological Properties</a>
