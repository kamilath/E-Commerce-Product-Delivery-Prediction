# E-Commerce Product Delivery Prediction

This repository contains a machine learning project that predicts the timely delivery of products in an e-commerce platform using various classification algorithms. The project is built using Python and utilizes popular libraries like `pandas`, `NumPy`, `seaborn`, `scikit-learn`, and `matplotlib`.

---

## Project Workflow

### 1. Data Preprocessing
- Loaded the dataset and performed exploratory data analysis (EDA).
- Cleaned the data by:
  - Dropping unnecessary columns (e.g., `ID`).
  - Checking for null values and duplicates.
  - Encoding categorical variables using `LabelEncoder`.

### 2. Data Visualization
- Created insights using:
  - Pie charts, histograms, countplots, violin plots, and heatmaps.
- Explored relationships between various features such as gender, product properties, logistics, customer experience, and delivery performance.

### 3. Feature Selection
- Used a correlation heatmap to identify significant relationships between features.

### 4. Model Building
- Split the dataset into training and testing sets (80:20 ratio).
- Implemented the following machine learning algorithms:
  - Decision Tree Classifier
  - Logistic Regression
  - K-Nearest Neighbor Classifier

### 5. Model Optimization
- Used `GridSearchCV` for hyperparameter tuning of the Decision Tree model.

### 6. Model Evaluation
- Evaluated the models using:
  - Accuracy score.
  - Confusion matrix visualization.
  - Classification report (Precision, Recall, F1-Score).
- Compared model performance using bar plots.

---

## Results

| Model                     | Accuracy |
|---------------------------|----------|
| Decision Tree Classifier  | 68%      |
| Logistic Regression       | 63%      |
| K-Nearest Neighbor        | 65%      |

The **Decision Tree Classifier** performed the best with optimized parameters.

---

## Visualizations
Key insights and findings are supported by:
- **Distribution plots** for product properties.
- **Countplots** for customer experience and logistics.
- **Violin plots** and **heatmaps** for feature relationships.

---

## Future Enhancements
- Adding more advanced models like **Random Forest** and **Gradient Boosting**.
- Incorporating **feature engineering** to improve predictions.
- Optimizing other models using **hyperparameter tuning**.

