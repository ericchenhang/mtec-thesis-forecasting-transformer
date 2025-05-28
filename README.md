
# Transformer-based Forecasting – Multichannel Dataset

This repository contains the core forecasting code used in the master's thesis  
**_Beyond the Horizon: Constructing Transformer Models to Forecast Retail Customer Behavior_** (ETH Zurich, MTEC).

**Dataset:** Specialty Multichannel Catalog Merchant  
**Included Notebooks:**
- Sequence Sampling Forecasting
- Cross-Cohort Forecasting

  <img width="1104" alt="Architecture_new" src="https://github.com/user-attachments/assets/9e899aa1-614e-4c33-b799-f8e363c30e27" />
---

## 📁 Folder Structure
```
├── notebooks/
│ ├── Sequence_Sampling_Forecasting_Multichannel.ipynb
│ └── Cross_Cohort_Forecasting_Multichannel.ipynb
├── data/
│ ├── 15-transactions_allCohorts.csv
│ ├── EL_transactions_allCohorts.csv
│
├── README.md
└── requirements.txt
```



---

## Note on Other Datasets

This repository currently includes code for the **Multichannel** dataset only.  
However, the forecasting pipelines for other datasets used in the thesis (such as **EL** and **AP**) follow an identical structure.

To replicate the experiments for other datasets:

1. Duplicate the provided notebooks (`.ipynb` files).
2. Replace the data path (e.g., `data/EL_transactions_allCohorts.csv` or `data/AP_transactions_allCohorts.csv`).
3. Adjust the cohort split ranges and other configuration parameters as needed (defined in the notebook's respective section).

---

_Last updated: May 2025_
