# Code and Data for:  
**Machine learning and big data-based stratifications to integrate justice into Integrated Assessment Models**

This repository contains the datasets, code, and outputs used in the study titled:  
*Machine learning and big data-based stratifications to integrate justice into Integrated Assessment Models*, submitted to **npj Climate Action**.

---

## 📁 Repository Structure

### 1. Original Data Folder

This folder contains the main input datasets used throughout the analysis:

- **File 1: merged_normalized_ecological_and_wdi_wide.csv**  
  Combined environmental and socioeconomic data, used as the primary input file for all analyses in this study.

- **File 2: Supplementary Data and Sources.docx**  
  Provides detailed definitions, descriptions, and sources for each variable included in the merged dataset.

---

### 2. Code Folder

This folder includes all Jupyter Notebooks used:

- **File 1-HC.ipynb**  
  Jupyter Notebook File (ipynb) for Hierarchical-Clustering 
- **File 2-TSC_DTW.ipynb**  
  Jupyter Notebook File (ipynb) for Time Series Cluster with Dynamic Time Warping (TSC-DTW)  
- **File 3-MOO.ipynb**  
  Jupyter Notebook File (ipynb) for Multi-objective Optimization (based on pymoo)
- **File 4-RMSE.ipynb**  
  Jupyter Notebook File (ipynb) for Urbanization Rate Projections  
- **File 5-Urb_Proj.ipynb**  
  Jupyter Notebook File (ipynb) for Calculating Root Mean Square Errors for Urbanization Rate Projections

---

### 3. The Justice-Stratified Country Groups Output File Folder

This folder includes the resulting groupings of countries based on the applied methods:

- **File 1-Lists_HC.docx**  
  The justice-stratified county group lists from the Hierarchical-Clustering  
- **File 2-Lists_TSC_DTW.docx**  
  The justice-stratified county group lists from the Time Series Cluster with Dynamic Time Warping (TSC-DTW)  
- **File 3-Lists_MOO_2003.docx**  
  The justice-stratified county group lists (2003) from the Multi-objective Optimization (based on pymoo)
- **File 4-Lists_MOO_2012.docx**  
  The justice-stratified county group lists (2012) from the Multi-objective Optimization (based on pymoo)
- **File 5-Lists_MOO_2022.docx**  
  The justice-stratified county group lists (2022) from the Multi-objective Optimization (based on pymoo)

Each file lists the resulting country groups formed under different methodological approaches, used in justice-based IAM scenario testing.

---

### 4. UrbanProj_Comparisons Folder

Contains RMSE results under various urbanization speed and Shared Socioeconomic Pathway (SSP) scenarios:

- **4.1 RMSE_FAST**  
  RMSE results under the *Fast Urbanization* scenario
- **4.2 RMSE_SLOW**  
  RMSE results under the *Slow Urbanization* scenario
- **4.3 RMSE_MOD**  
  RMSE results under the *Moderate Urbanization* scenario
- **4.4 RMSE_SSP4**  
  RMSE results under the *SSP-4* scenario

Each subfolder contains the RMSE results comparing urbanization projections from Hierarchical Clustering, DTW Clustering, and MOO methods, as well as projections from Jian & O'Neill and Chen et al., against historical urbanization data from the World Bank.

---
