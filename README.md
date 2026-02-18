# Okeanos_Alaska
**Okeanos Alaska: Deep-Sea Coral and Sponge Communities**

This repository contains the data, R scripts, and reproducible workflow used to analyze biological annotation data from NOAA Okeanos Explorer dives EX2304 and EX2306, conducted across the Gulf of Alaska and Aleutian Islands. The analyses focus on community composition, diversity, and environmental drivers of deep-sea coral and sponge assemblages.

**Zenodo Archive**

The processed datasets and derived environmental variables are also archived in Zenodo (DOI: 10.5281/zenodo.18221896), which includes morphotype-level observations, depth-binned summaries, and dive-level aggregations. Raw CTD and multibeam bathymetry data are publicly available via NOAA repositories and can be requested from the authors if needed.

**Preprint**

A preprint describing the associated analyses is available at SSRN: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5317177

**Repository Structure**

*Raw Data/*

Contains all necessary input files used in the analysis, including biological annotations from ROV video surveys and derived environmental variables (depth, temperature, salinity, oxygen, substrate type, and terrain metrics). The full CTD profiles can be downloaded from NOAA and transformed to .cnv (or contact me for the full file, they are too large to upload here). 

*Code/*

Includes the main R scripts and R Markdown files used for data processing, analysis, and visualization:

*  Okeanos_Script_1.Rmd – Extracts and processes multibeam data (bathymetry and backscatter) for use as environmental predictors.

*  Okeanos_Script_2.Rmd – Performs data curation, exploratory analysis, beta diversity calculations, statistical modeling, and plotting.

Each .Rmd file is accompanied by a rendered HTML version for easy navigation of code, outputs, and figures.

**Usage**

You are free to use, adapt, and share these materials for non-commercial purposes, provided proper credit is given. Please cite the Zenodo dataset and the preprint (or the forthcoming peer-reviewed paper) when using this data or code in your work.

For questions regarding the code, data, or workflow, contact: laramaleenbeck@gmail.com




