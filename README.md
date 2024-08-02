# fMRIproc_MSc_Thesis

## Codes used in my MSc for preprocessing and seed-based fMRI analysis

This repository contains the source code and scripts used in my master's thesis for preprocessing and analyzing medical images. The project involves converting DICOM images to NifTI format, organizing images in BIDS format, quality evaluation, intensity uniformity corrections, skull stripping, tissue segmentation, and more, using RStudio, FSL, and Python 3.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Contact](#contact)

## Installation

To use these scripts, you will need to have RStudio, FSL, and Python 3 installed. Here are the basic steps to set up the required environment.

### Prerequisites
- FSL

### Installation Steps
1. Install FSL following the instructions at [fsl.fmrib.ox.ac.uk](https://fsl.fmrib.ox.ac.uk)

## Usage

Scripts are organized by preprocessing and analysis stages:

### Data Conversion
- `dcm2bids.SGE`: Script for converting DICOM images to BIDS format.

### Basic Preprocessing
- `fsl_pp.sh`: Script for preprocessing fMRI data using FSL.
- `fsl_pp_edit.sh`: Edited version of `fsl_pp.sh` with custom modifications.

### Registration and Normalization
- `antsReg.SGE`: Script for registration of images using ANTs.
- `antsNormCone.SGE`: Script for normalization of images using ANTs.

### Quality Control
- `mriqcTMS.SGE`: Script for quality control of MRI data using MRIQC.

### ROI Analysis/Extraction
- `cone_roi_csv.sh`: Script for extracting regions of interest (ROI) and generating CSV files.

### Statistical Analysis/Correlation Mapping
- `corrMapsMean.sh`: Script for generating correlation maps and calculating mean values.
- `corrMapsMean2.sh`: Alternative script for generating correlation maps with different parameters.

### Advanced Analysis (e.g., Connectivity)
- `stimZoneHCcorrs_CPACaddimexConn.sh`: Script for connectivity analysis using CPAC with additional parameters for stimuli zones.
- `stimZoneHCcorrs_CPACaddimexrTMS.sh`: Script for connectivity analysis using CPAC with rTMS-specific parameters.
- `stimZoneHCcorrs_FSLaddimexrTMS.sh`: Script for connectivity analysis using FSL with rTMS-specific parameters.
- `xcpEngineAnatTMS.SGE`: Script for anatomical processing using XCP Engine with rTMS-specific parameters.
- `xcpEngineFuncTMS.SGE`: Script for functional processing using XCP Engine with rTMS-specific parameters.

## Contact

If you have any questions or would like to collaborate on the project, feel free to reach out.
