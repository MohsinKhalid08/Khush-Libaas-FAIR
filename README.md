
# Khush Libaas – AI-Powered Fashion Recommendation System

This repository contains all FAIR-related artifacts for the Khush Libaas experiment, created as part of the 2025 FAIR Data Science Exercise at TU Wien.

---

## Project Overview
Khush Libaas is a personalized fashion recommendation system for Pakistani users. It leverages structured metadata (brand, color, fabric, style, etc.) to classify traditional outfits by event type (e.g., Wedding, Eid, Formal).

For Part-2, a simulated KNN-based pipeline was created, with all data and outputs made FAIR: Findable, Accessible, Interoperable, and Reusable.

---

## Dataset PIDs on DBRepo (TU Wien)

| Dataset Type | PID |
|--------------|-----|
| Training | https://test.dbrepo.tuwien.ac.at/pid/9b858643-5ff0-495a-bcef-8c2e77d85713 |
| Validation | https://test.dbrepo.tuwien.ac.at/pid/0a1a4634-38cc-486a-9e4c-746819d350b4 |
| Test | https://test.dbrepo.tuwien.ac.at/pid/2e5a8c3f-9072-4d6d-ae5d-4d0342127cba |

Each dataset contains metadata including brand, price, size, color, gender, fabric type, and regional popularity.

---

## Outputs Included

| Filename | Description |
|----------|-------------|
| khush_libaas_model.pkl | Trained KNN model file (simulated on synthetic data) |
| evaluation_metrics.json | Evaluation metrics (accuracy, precision, recall, F1) |
| confusion_matrix.png | Visualization of true vs predicted event types |
| feature_importance_chart.png | Frequency-based importance of encoded features |
| recommendations.csv | Top-5 recommended clothing samples with scores |

---

## Tools & Technologies

- Language: Python
- ML Model: K-Nearest Neighbors (KNN)
- Libraries: scikit-learn, pandas, matplotlib, seaborn
- Notebook: Jupyter (notebook included in GitHub submission)

---

## FAIR Compliance

This project complies with FAIR principles via:

- Data deposition on DBRepo (TU Wien)
- Output metadata uploaded to TUW Research Data
- Metadata models used: FAIR4ML, CodeMeta, Croissant
- All datasets have valid PIDs and are cited in the notebook

---

## Licensing

- Code & Scripts: MIT License
- Data & Visuals: Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## Author

Mohsin Khalid  
TU Wien — Matriculation No: 12443164

---

## Contact

For questions, contact via TU Wien email.
