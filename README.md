# TS-Clustering-LSM-PSInSAR-Dataset

This repository contains the dataset used for the article:

**Title:**  
*A spatiotemporal clustering and semi-supervised labeling strategy for landslide susceptibility mapping using PS-InSAR and contextual factors*

## 📦 Dataset Content

The dataset includes four `.pkl` files used in the TS-Clustering and contextual analysis process:

### Contextual Factors – VIF Analysis
- `factors_vif_data_2024.pkl`: Raw contextual variables with multicollinearity analysis (VIF)
- `factors_vif_norm_data_2024.pkl`: Normalized version of the same dataset

### Ground Dynamics – PS-InSAR Trajectories
- `factors_ground_data_2024.pkl`: Raw ground deformation factors extracted from PS-InSAR
- `factors_ground_data_norm_2024.pkl`: Normalized PS-InSAR time-series features

These datasets were used to perform semi-supervised clustering, multicollinearity testing, and ground dynamics trajectory analysis for landslide susceptibility mapping.

## 🧪 File Format

All files are in Python `pickle` format (`.pkl`), readable using `pandas`:

```python
import pandas as pd
df = pd.read_pickle('factors_vif_data_2024.pkl')
