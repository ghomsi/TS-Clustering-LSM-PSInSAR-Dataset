# TS-Clustering-LSM-PSInSAR-Dataset

This repository contains the dataset used for the article:

**Title:**  
*A spatiotemporal clustering and semi-supervised labeling strategy for landslide susceptibility mapping using PS-InSAR and contextual factors*

## 📦 Dataset Content

The dataset includes four `.pkl` files used in the TS-Clustering and contextual analysis process:

### Contextual Factors – VIF Analysis
- `factors_contextual_vif_data_2019.pkl`: Raw contextual variables with multicollinearity analysis (VIF)
- `factors_contextual_vif_normalized_data_2019.pkl`: Normalized version of the same dataset

### Ground Dynamics – PS-InSAR Trajectories
- `factors_ground_deformation_data_2019.pkl`: Raw ground deformation factors extracted from PS-InSAR
- `factors_ground_deformation_data_2019_normalized.pkl`: Normalized PS-InSAR time-series features


## 🧪 File Format

All files are in Python `pickle` format (`.pkl`), readable using `pandas`:

```python
import pandas as pd
df = pd.read_pickle('factors_contextual_vif_data_2019.pkl')
```

## 🧪 Applications

These datasets were used to perform semi-supervised clustering, multicollinearity testing, and ground dynamics trajectory analysis for landslide susceptibility mapping.

## 🔗 DOI and Dataset Archive

A permanent, citable archive of this dataset is available via Zenodo:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16216682.svg)](https://doi.org/10.5281/zenodo.16216682)

Zenodo link: https://doi.org/10.5281/zenodo.16216682

## 📄 License

This dataset is shared under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

> You are free to use, share, and adapt the data, provided appropriate credit is given to the authors.

## 📚 Citation

If you use this dataset, please cite the following article:

**[Authors]**, *Spatio-Temporal Landslide Susceptibility Mapping Using TS-Clustering and Contextual
Factors with PS-inSAR: A Data-Driven Approach to Labeling Unlabeled Data*, Science of Remote Sensing, 2025.  
**DOI:** [To be added upon publication]

---

