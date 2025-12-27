# README

## Overview

This repository contains TCIA manifest (`.tcia`) files used to download publicly available CT imaging datasets from [The Cancer Imaging Archive (TCIA)](https://www.cancerimagingarchive.net/) using the [NBIA Data Retriever](https://wiki.cancerimagingarchive.net/display/NBIA/Installing+the+NBIA+Data+Retriever). These manifest files enable reproducible access to the datasets without including the imaging data directly in the repository.

## Included Manifest Files

### 1. `NSCLC-Radiomics-Version-4-Oct-2020-NBIA-manifest.tcia`
- TCIA manifest for the **NSCLC Radiomics** collection (Version 4, October 2020).  
- Contains metadata to download CT images and associated radiomics data for non-small cell lung cancer (NSCLC) research.
- Public Access [NSCLC-Radiomics](https://www.cancerimagingarchive.net/collection/nsclc-radiomics/)

### 2. `manifest-NLST_allCT.tcia`
- TCIA manifest for the **National Lung Screening Trial (NLST)** collection.  
- Contains metadata to download all available CT imaging studies from the NLST dataset.
- Public Access [NLST_allCT](https://www.cancerimagingarchive.net/collection/nlst/)

## Usage

1. Install the [NBIA Data Retriever](https://wiki.cancerimagingarchive.net/display/NBIA/Installing+the+NBIA+Data+Retriever).
2. Launch the Data Retriever application.
3. Open one of the `.tcia` manifest files from this repository.
4. Choose a download location and start downloading the corresponding dataset.

## Notes

- The repository only contains manifest files, not the imaging data itself. The actual data will be downloaded directly from TCIA.
- Access to TCIA data is subject to [TCIA data usage policies and licenses]([https://www.cancerimagingarchive.net/using-the-data/](https://www.cancerimagingarchive.net/access-data/)).
