
# Khush Libaas – FAIR Fashion Recommendation System

**Khush Libaas** is a personalized fashion recommendation system designed for traditional Pakistani clothing, developed as part of the FAIR Data Science course at TU Wien. This repository implements a machine learning pipeline following FAIR principles using Python and Jupyter Notebook.

---

## 💡 Project Objective

To recommend appropriate clothing based on metadata such as:
- Brand, Color, Size, Gender
- Fabric Type, Style, Region Popularity
- Event Type (e.g. Wedding, Eid, Office)

The final model is trained using K-Nearest Neighbors (KNN) and evaluated on accuracy, feature importance, and classification performance.

---

## 📁 Repository Structure

```bash
.
├── khush_libaas_fair.ipynb          # Final Jupyter notebook (FAIR-compliant)
├── khush_libaas_train.csv           # Training dataset
├── khush_libaas_valid.csv           # Validation dataset
├── khush_libaas_test.csv            # Test dataset
├── khush_libaas_model.pkl           # Trained model
├── evaluation_metrics.json          # Model evaluation metrics
├── confusion_matrix.png             # Confusion matrix visualization
├── feature_importance_chart.png     # Feature importance bar plot
├── recommendations.csv              # Top 5 recommended outfits
├── LICENSE                          # MIT license
├── codemeta.json                    # CodeMeta metadata block
└── README.md                        # This documentation
```

---

## 🚀 Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/MohsinKhalid08/Khush-Libaas-FAIR.git
   cd Khush-Libaas-FAIR
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt  # (manually create if needed)
   ```

3. Run the notebook:
   ```bash
   jupyter notebook khush_libaas_fair.ipynb
   ```

4. View outputs:
   - `evaluation_metrics.json`
   - `confusion_matrix.png`
   - `recommendations.csv`
   - `feature_importance_chart.png`

---

## 🔗 Dataset PIDs (From DBRepo TU Wien)

| Dataset | PID |
|---------|-----|
| Training | https://test.dbrepo.tuwien.ac.at/pid/9b858643-5ff0-495a-bcef-8c2e77d85713 |
| Validation | https://test.dbrepo.tuwien.ac.at/pid/0a1a4634-38cc-486a-9e4c-746819d350b4 |
| Test | https://test.dbrepo.tuwien.ac.at/pid/2e5a8c3f-9072-4d6d-ae5d-4d0342127cba |

---

## 🧠 Technologies Used

- Python (3.x)
- Jupyter Notebook
- scikit-learn
- pandas, seaborn, matplotlib

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.

---

## 👤 Author

**Mohsin Khalid**  
TU Wien – Student ID: 12443164  
ORCID: https://orcid.org/0009-0000-9775-1879
GitHub: [@MohsinKhalid08](https://github.com/MohsinKhalid08)

---

## ✅ FAIR Compliance Highlights

- ✅ Dataset published with PIDs via DBRepo
- ✅ Outputs published to TUWRD (DOI: [10.70124/r6mjm-2zx16](https://doi.org/10.70124/r6mjm-2zx16))
- ✅ CodeMeta metadata included
- ✅ Data Management Plan (DMP) submitted via Zenodo

For questions or contributions, feel free to open an issue or fork the repo.

