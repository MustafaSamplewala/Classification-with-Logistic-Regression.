# Classification-with-Logistic-Regression.

## 📌 Objective
Build a binary classifier using logistic regression on the Breast Cancer dataset.

---

## 📁 Dataset
- **Source**: Provided as `data.csv`
- **Target Column**: `diagnosis`
  - Encoded: `M` = 1 (Malignant), `B` = 0 (Benign)
- **Rows**: 569
- **Features**: 30 (after dropping ID and empty column)

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## ✅ Steps Performed

1. **Data Loading**  
   - Loaded and cleaned dataset.
   - Dropped irrelevant columns: `id`, `Unnamed: 32`.

2. **Label Encoding**  
   - Converted diagnosis labels from `'M'`/`'B'` to `1`/`0`.

3. **Train-Test Split**  
   - 80% training, 20% testing using `train_test_split()`.

4. **Feature Scaling**  
   - Standardized features using `StandardScaler`.

5. **Model Training**  
   - Trained a Logistic Regression model.

6. **Evaluation Metrics**  
   - Confusion Matrix
   - Classification Report
   - Precision, Recall
   - ROC-AUC Score
   - ROC Curve plot

7. **Sigmoid Function Visualization**  
   - Plotted sigmoid curve used by logistic regression.

---

## 📈 Results

- **Precision**: ~0.96  
- **Recall**: ~0.94  
- **ROC AUC**: ~0.99  
- **Model** performs well on this medical diagnosis task.
