# network-traffic-anamoly-detection-ieee-replication🔒
Independent reproducibility study validating the machine learning framework proposed in IEEE paper - Anomaly Detection in Network Traffic Using Advanced Machine Learning Techniques (S. Ness et al)

This repository contains an independent reconstruction and validation framework of the methodology proposed in the peer-reviewed IEEE paper: 
> **"Anomaly Detection in Network Traffic Using Advanced Machine Learning Techniques"** (S. Ness et al, 2025)

The objective of this project was to stress-test the original findings and evaluate the robustness of the machine learning models utilizing standard Python libraries, to verify the claim.

## 🛠️ Tech Stack & Dependencies
* **Language:** Python
* **Machine Learning:** scikit-learn (sklearn)
* **Data Processing:** Pandas, NumPy, SMOTE
* **Environment:** Google Colab / Jupyter Notebooks

### Key Findings
* The independent pipeline achieved **near-accurate results** matching the baseline models, validating the mathematical soundness of the paper's feature engineering techniques.
* Minor variances in final metrics are attributed to random state initialization over non-disclosed PCA.

## 📁 Repository Structure
* `ML_Reproducibility_study_MJ`: Contains the fully documented step-by-step Google Colab execution pipeline.
* `ml_reproducibility_study`: Production-ready Python scripts for the model architecture.
* `requirements.txt`: Environment configuration for local replication.
