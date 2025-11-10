# 🌱 Smart Irrigation — Machine Learning Project

## 🧭 Overview
This project aims to **predict the amount of water required for irrigation (L/m²)** using machine learning models trained on soil and weather data.  
By combining data preprocessing, feature engineering, and explainable AI techniques, the model helps optimize water usage for sustainable agriculture.

---

## 📂 Project Structure
```
smart_irrigation.ipynb        # Main Jupyter Notebook
smart_irrigation_dataset_30000.csv  # Dataset used (synthetic)
README.md                     # Project documentation
```

---

## 🧠 Features & Workflow
1. **Data Loading & Exploration**
   - Reads dataset and explores distributions, correlations, and trends.
2. **Data Preprocessing**
   - Encodes categorical variables using `OneHotEncoder`
   - Scales numeric features using `StandardScaler`
3. **Model Training**
   - Models used:
     - `RandomForestRegressor`
     - `GradientBoostingRegressor`
4. **Evaluation**
   - Metrics: RMSE and R²
   - Feature importance visualization
5. **Explainability**
   - SHAP (SHapley Additive exPlanations) used for feature-level interpretation

---

## ⚙️ Requirements

Install dependencies using pip:

```bash
pip install requirements.txt
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Place the dataset (`smart_irrigation_dataset_30000.csv`) in the same directory as the notebook.
3. Open the Jupyter notebook:

```bash
jupyter notebook smart_irrigation.ipynb
```
4. Run all cells sequentially to reproduce the workflow.

---

## 📊 Results
- The model outputs predicted irrigation water needs (L/m²).
- Evaluation metrics include:
  - **Root Mean Squared Error (RMSE)**
  - **R² Score**
- SHAP visualizations highlight which soil and weather factors most influence irrigation requirements.

---

## 🪴 Future Improvements
- Integrate real-world IoT sensor data.
- Add rainfall and evapotranspiration forecasting.
- Deploy as a web or mobile app for farmers.
- Experiment with neural networks (e.g., `XGBoost`, `LSTM`).

---

## 📚 References
- [Scikit-learn documentation](https://scikit-learn.org/)
- [SHAP documentation](https://shap.readthedocs.io/)

---

