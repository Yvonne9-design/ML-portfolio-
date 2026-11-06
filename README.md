# Machine Learning Portfolio: Regression, Classification, & Clustering

A collection of three distinct machine learning pipelines implemented in Python using scikit-learn, covering regression, classification, and unsupervised clustering tasks.

## 📁 Project Structure
- `project_notebook.ipynb`: Main Jupyter Notebook containing data preprocessing, model training, evaluation, and visualizations.
- `requirements.txt`: Python package dependencies.
- `README.md`: Project documentation.

---

## 🔍 Task Breakdown

### 1. Wine Quality Dataset (Regression)
* **Objective:** Predict wine quality scores based on physicochemical properties.
* **Approach:** Applied `StandardScaler` to prevent data leakage, trained Linear Regression and Random Forest Regressor models.
* **Evaluation Metrics:** MAE, RMSE, and $R^2$ score, supplemented by 5-fold cross-validation.
* **Key Finding:** Non-linear ensemble methods (Random Forest) generalized significantly better on this dataset compared to linear models.

### 2. Raisin Dataset (Classification)
* **Objective:** Classify raisin varieties (Kecimen vs. Besni) using morphological features.
* **Approach:** Used stratified train-test splitting to preserve class balance, implemented Logistic Regression and Gaussian Naive Bayes.
* **Evaluation Metrics:** Confusion matrix, Precision, Recall, F1-Score, and ROC-AUC via stratified cross-validation.

### 3. Wholesale Customers Dataset (Clustering)
* **Objective:** Segment wholesale customers based on annual spending characteristics.
* **Approach:** Standardized features for distance-based clustering, applied K-Means.
* **Evaluation Metrics:** Optimized hyperparameter $k$ (ranging from 2 to 8) using the Elbow Method and Silhouette Scores, visualized via 2-D PCA.

---

## 🛠️ Getting Started & Replication

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Yvonne9-design/your-repo-name.git](https://github.com/Yvonne9-design/your-repo-name.git)
   cd your-repo-name
# ML-portfolio-