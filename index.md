---
title: Emma Schillerstrom
---

# Presentations

Reproducible Workflows in R [(View GitHub)](https://github.com/USFWS/data-workflow-presentation)

Introduction to Quarto [(View GitHub)](https://github.com/USFWS/intro-to-quarto)

# Technical Products

## National Wildlife Refuge (NWR) Data Workflows

#### Teltin NWR Wood Bison (*Bison bison athabascae*) Reintroduction Habitat Assessment
R scripts with reusable functions to
- compile and tidy hundreds of individual snow probe data directly from third-party Propagation Labs Snow Scope app exports
- plot individual snow hardness depth profiles in kPa or on a log-adjusted Hand Hardness scale
- plot averaged (with error bands) snow hardness depth profiles for pooled plots or sites

#### Tetlin NWR Snowshoe Hare (*Lepus americanus*) Monitoring Survey
Reusable R scripts to 
- compile, tidy, and generate summary tables for all 33 years of historic hare pellet data
- calculate hare densities and 
- visualize the population cycle via a density time series plot

#### Tetlin NWR Trumpeter Swan (*Cygnus buccinator*) Census Survey
R scripts to
- compile and tidy newly-collected data with historic (36 years) Migratory Bird Program data

R Quarto report to
- perform exploratory data analysis, providing summary tables, correlation matrices, and visualizations for abundance and productivity information
- compare datasets subsetted by percent volume contours, USGS quadrangles, or flightpath buffers
- provide automated summary blurb with inline code calculations

#### Kenai NWR Trumpeter Swan (*Cygnus buccinator*) Monitoring Survey
R scripts to compile, tidy, and QC 67 years of data
R Quarto report with maps, tables, and information on alterations to the data, summary totals over time, spatial coverage, temporal coverage, lake occupancy, and duplicate and outlier observations
ArcGISPro map visualizing annual survey coverage and spatially joining swan dataset with landable lake polygon features and their attributes

#### Kenai NWR Fire Impacts to Dall Sheep (*Ovis dalli dalli*) Research Project
R Quarto report to tidy sheep feces parasite data with embedded leaflet maps visualizing parasite load relative to wildfire burn sites

#### Yukon Delta NWR Mark-Recapture Rotary Screw Trap Juvenile Salmon (*Oncorhynchus*) Monitoring Survey
Reusable R code to tidy entered data and automate state permit reporting, eliminating weeks of manual data entry for over 43,000 fish by staff in 2024 and all subsequent years

#### (*In Progress*) Alaska Peninsula/Becharof NWR Willow Ptarmigan (*Lagopus lagopus*) Monitoring Survey
R scripts to compile and tidy several years of distance sampling data
Reusable R code to create an eBird checklist, fit detection functions, calculate bird densities, and generate an AIC table for any given year

## USFWS Apps/Dashboards

#### ServCat Shiny Dashboard for Refuge Managers
Two R Shiny dashboards which call APIs to visualize data from national FWS databases and monitor regional data management progress; dashboards hosted on PositConnect and uploaded to USFWS GitHub; presented at 2023 national Inventory and Monitoring data manager meeting

#### ServCat Shiny Dashboard for Regional Office

#### Survey Product Preservation Monitoring App [(View GitHub)](https://github.com/USFWS/check-survey-preservation)
Cross-regional R Shiny app that produces summary reports of survey product preservation and generates data asset inventory Excel workbooks with custom dropdown lists and auto-filled data from FWS databases; presented nationally with multiple regions expressing interest in adoption

## Other

#### DFP Bioinformatics Project: Black Carp Genome Assembly Pipeline
2 Bash scripts and 1 Python script

#### (*In Progress*) Streamlining Document Selection for Preservation
Python script to streamline the initial process for preserving large (>100,000) batches of historic digital files by automating parsing through file directories, eliminating empty folders, and selecting and organizing the file types appropriate for repository preservation
