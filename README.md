# fMRIproc_MSc_Thesis
Codes used in my MSc for preprocessing and seed based fMRI analysis

This repository contains the source code and scripts used in my master's thesis for preprocessing and analyzing medical images. The project involves converting DICOM images to NifTI format, organizing images in BIDS format, quality evaluation, intensity uniformity corrections, skull stripping, tissue segmentation, and more, using RStudio, FSL, and Python 3.
Table of Contents
* Installation
* Usage
* Contact
  
Installation
To use these scripts, you will need to have RStudio, FSL, and Python 3 installed. Here are the basic steps to set up the required environment.
Prerequisites
* Python 3.x
* RStudio
* FSL
  
Installation Steps
* 		Install Python 3.x from python.org
* 		Download and Install RStudio from https://posit.co/products/open-source/rstudio/
* 		Install FSL following the instructions at fsl.fmrib.ox.ac.uk
  
Usage
Scripts are organized by preprocessing and analysis stages:
*    Data Conversion: dcm2bids.SGE
*    Basic Preprocessing: fsl_pp.sh and fsl_pp_edit.sh
*    Registration and Normalization: antsReg.SGE and antsNormCone.SGE
*    Quality Control: mriqcTMS.SGE
*    ROI Analysis/Extraction: cone_roi_csv.sh
*    Statistical Analysis/Correlation Mapping: corrMapsMean.sh
*    Advanced Analysis (e.g., Connectivity): stimZoneHCcorrs_CPACaddimexConn.sh
  
Contact
If you have any questions or would like to collaborate on the project, feel free to reach out.
