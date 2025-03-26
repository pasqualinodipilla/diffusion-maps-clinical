# diffusion-maps-clinical
Implementation of diffusion maps and application to clinical data

# Diffusion Maps

This project explores the theory and implementation of **Diffusion Maps**, 
a nonlinear dimensionality reduction technique, applied to both 
**synthetic data** and **real-world clinical datasets**.

It covers the full data pipeline:
- Data extraction and cleaning using **SQL**
- Standardization with **SAS** (SDTM/ADaM simulation)
- Visualization and reduction using **Diffusion Maps** in **Python**
- Comparison with PCA/UMAP in **R**
- Git-based versioning and project structure

---

## Project Structure

/data		→ Original CSVs and SQLite database

/notebooks	→ Jupyter Notebooks (geometry, images, clinical data)

/src		→ Custom Python implementation of Diffusion Maps

/sql		→ SQL scripts to create and query the clinical database

/sas		→ SAS code for CDISC-style datasets (DM,LB,ADSL...)

/r		→ R scripts for PCA/UMAP comparisons

/output		→ Plots, exports, and results 

---

## Notebooks Overview

- '1_geometry_test.ipynb' : 3D closed curve → 2D projection using my own 
algorithm
- '2_images_test.ipynb' : Diffusion Map on facial images dataset
- '3_clinical_sql.ipynb' :  SQL queries on patient database
- '4_diffusionmap_clinical.ipynb' : Dimensionality reduction on merged 
clinical data

---

## Technologies

- **Python**: NumPy, pandas, matplotlib, scikit-learn
- **SQL**: SQLite
- **SAS**: PROC IMPORT, CDISC (SDTM/ADaM), export to XPT
- **R**: PCA, UMAP, ggplot2

---

## Goals

- Understand and implement the core ideas behind Diffusion Maps
- Validate the implementation on known geometric structures
- Apply to real clinical data and explore latent progressions
- Show how data standards (CDISC) and analytics tools work together

---

## Author

Created by Pasqualino Di Pilla - as a personal and academic exploration of 
dimensionality reduction in biomedical contexts.
