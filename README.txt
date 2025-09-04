# Credit Card Fraud Detection: A Machine Learning Approach

##  Overview
This project implements a **credit card fraud detection system** using Python and machine learning.  
It leverages a **Random Forest Classifier** to identify fraudulent transactions with **99.98% accuracy**, incorporating:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Interactive visualizations

The project is modular, reproducible, and suitable for both academic and professional purposes.

---

##  Dataset
- **Source:** [Kaggle - Credit Card Fraud Detection Dataset 2023](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023)  
- **Features:** 30 columns (28 anonymized features V1–V28, plus Amount, Time, and Class)  
- **Target variable:** Class (0 = legitimate, 1 = fraudulent)  
- **Size:** ~568,630 transactions (balanced dataset)  

 **Note:** Due to licensing restrictions, the dataset is **not** included in this repository. Please download it manually from Kaggle.

---

##  Methodology
1. **Data Preprocessing**
   - Removed duplicates & missing values
   - Standardized numerical features with StandardScaler
2. **Exploratory Data Analysis (EDA)**
   - Missing values heatmap
   - Correlation matrix
   - Distribution histograms
   - Pie charts for categorical variables
   - Outlier detection with IQR method
3. **Model Development**
   - Random Forest Classifier (scikit-learn)
   - 80/20 train-test split
   - Metrics: Accuracy, Precision, Recall, F1-score
4. **Visualization Enhancements**
   - Interactive plots with ipywidgets and mpld3

---

##  Results
- **Accuracy:** 0.9998  
- **Precision / Recall / F1-score:** 1.00 for both classes

These results indicate near-perfect classification performance.

---