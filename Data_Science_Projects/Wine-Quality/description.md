#  Wine Quality Prediction and Clustering

## **Objective**
This project analyzes wine quality using both **unsupervised (clustering)** and **supervised (classification)** learning methods to identify patterns and predict quality levels based on physicochemical features.

---

## **Dataset**
- **Source:** [UCI Machine Learning Repository – winequality-red.csv](https://archive.ics.uci.edu/ml/datasets/wine+quality)  
- **Records:** 1,599 red wine samples  
- **Features:** 11 numerical attributes + 1 target variable (`quality`)

---

## **Tech Stack**
- **Language:** Python  
- **Libraries:** `pandas`, `NumPy`, `matplotlib`, `scikit-learn`  
- **Environment:** Jupyter Notebook  

---

## **Methodology**

### 🔹 Data Preprocessing
- Handling missing values  
- Normalization and feature scaling  

### 🔹 Dimensionality Reduction
- Performed **PCA (Principal Component Analysis)** for 2D visualization  

### 🔹 Clustering Analysis
- **Techniques Used:**
  - KMeans  
  - Agglomerative Clustering  
  - DBSCAN  
- **Evaluation Metrics:**
  - Silhouette Score  
  - Davies-Bouldin Index  

### 🔹 Classification Analysis
- **Models Applied:**
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Support Vector Machine (SVM)  
- **Evaluation Metrics:**
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Confusion Matrix  

### 🔹 Visualization
- Cluster plots (2D PCA projections)  
- Correlation heatmaps  
- Model performance comparison charts  

---

## **Expected Output**
- Visualized clusters via PCA  
- Detailed classification reports with performance metrics  
- Comparative analysis of clustering and classification techniques  

---

## **Applications**
- Enhancing **quality control** in winemaking  
- **Predicting wine grades** based on composition  
- Discovering **data-driven insights** for production optimization  

---

**Author:** Mahnoor Arif  
**Dataset License:** Open Data – UCI Repository [11]  
