# WDBC Binary Classification Project
 
## 1. Project Title
Breast Cancer Wisconsin (WDBC) Binary Classification using scikit-learn
 
## 2. Project Purpose
This project trains and compares multiple machine learning classifiers to
predict whether a breast tumour is **malignant** (cancerous) or **benign**
(non-cancerous) based on 30 numeric features computed from digitised images
of fine needle aspirate (FNA) biopsies.
 
## 3. Dataset Used
- **Name**: Breast Cancer Wisconsin Diagnostic (WDBC)
- **Source**: Built-in `sklearn.datasets.load_breast_cancer()`
- **Samples**: 569
- **Features**: 30 (mean, standard error, and worst values of 10 cell-nucleus measurements)
- **Classes**: 0 = malignant, 1 = benign
## 4. How to Install Requirements
```bash
pip install -r requirements.txt
```
 
## 5. How to Run the Code
open and run `wdbc_classification.ipynb` in Jupyter Notebook / Google Colab.
 
## 6. Output Files
| File | Description |
|------|-------------|
| `wdbc_classification_scatter.png` | Scatter plot of test data (mean radius vs mean texture) |
| `wdbc_classification_matrix.png`  | Confusion matrix of the best model |

 
## 7. Best Classifier Result
| Classifier    | Accuracy | Precision | Recall |
|---------------|----------|-----------|--------|
| SVM           | 95%      | 0.92      | 1.00   |
| Decision Tree | 95%      | 0.96      | 0.96   |
| KNN           | 96%      | 0.93      | 1.00   |
| Random Forest | 96%      | 0.96      | 0.99   |
 
**Best model: Random Forest with 96% accuracy on the test set.**
