# Machine-Learning-energy-generation-classification-DE-2023-2024
Predict Germany’s cross-border electricity status (Import/Export) using solar, wind, and load data from 2023–2024. Applied ML models including logistic regression, decision trees, and XGBoost for classification and evaluation

##  Project Goal

- Use only allowed input features (solar, wind, load)
- Predict whether Germany is in **Import** or **Export** mode
- Build, compare, and deploy multiple ML classification models

---

##  Tasks Breakdown

###  Task 1: Data Preparation + EDA
- Created binary labels: `Import` vs `Export`
- 3 custom visualizations:
  - Continuous and binary target heatmaps (DoY × Time)
  - Feature distribution vs label correlation
- Explored energy demand vs renewable supply

---

###  Task 2: Logistic Regression & k-NN
- Built logistic regression model with optimal regularization
- Applied k-Nearest Neighbors and tuned `k`
- Plotted train/test accuracy + confusion matrix
- Evaluated models using precision, recall, F1, ROC AUC

---

### Task 3: Decision Tree Classifier
- Trained a decision tree with hyperparameter tuning
- Visualized the tree & explained feature importance
- Compared results on 2024 test data

---

###  Task 4: Compare 5 Classification Models
- Evaluated:
  - SVM
  - Random Forest
  - Gradient Boosting (XGBoost)
  - ANN (Keras MLP)
  - LDA/QDA
- Cross-validation and hyperparameter tuning used for all
- Selected the best based on accuracy + ROC AUC

---

###  Task 5: Deployment on 2024 Data
- Saved the best model as `best_model`
- Applied it to 2024 test set
- Visualized prediction timeline and error patterns

---

##  Features Used (ONLY allowed features)
- `Actual Load [MW]`
- `Solar - Actual Aggregated [MW]`
- `Wind Onshore - Actual Aggregated [MW]`
- `Wind Offshore - Actual Aggregated [MW]`

 No fossil, hydro, or storage-related features included.

---

##  Tools Used

- Python 3.9
- pandas, seaborn, matplotlib
- scikit-learn
- xgboost
- keras / tensorflow
- Jupyter Notebook

---

##  Skills Demonstrated

- Feature engineering & binary label creation
- Time-based heatmap visualizations
- ML modeling: Logistic Regression, kNN, Decision Trees, SVMs, XGBoost
- Cross-validation, model selection, and deployment

---

## 👨‍💻 Authors

- **Ramesh  Nandiwale**   
- **Yasir Ali** 
- **Sadiq Shaikh** 

🧾 Course: Energy Data Engineering 2  
🎓 Offenburg University of Applied Sciences | 2024

---



