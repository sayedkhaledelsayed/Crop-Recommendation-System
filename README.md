# Crop-Recommendation-System
# 🌾 Crop Recommendation System (99.32% Accuracy)

---

## 📌 Project Overview
This project is a **Machine Learning Solution** designed to assist farmers in choosing the most suitable crop to grow based on soil and environmental conditions. Using precision agriculture data, we built a multi-class classifier that recommends one of **22 different crops**.

## 📊 Dataset Features
The model uses 7 key parameters to make predictions:
*   **Nutrients:** Nitrogen (N), Phosphorous (P), Potassium (K).
*   **Conditions:** Temperature (°C), Humidity (%), Rainfall (mm).
*   **Soil:** pH value.

## 🚀 Key Achievements
*   **Data Analysis:** Performed deep EDA to understand crop-specific requirements.
*   **Multi-Model Comparison:** Evaluated Logistic Regression, Decision Trees, and Random Forest.
*   **Top Performance:** The **Random Forest** model achieved a peak testing accuracy of **99.32%**.
*   **Deployment Ready:** Exported the final model and LabelEncoder as `.pkl` files using **Pickle**.

## 🛠️ Tech Stack
*   **Language:** Python 3.x
*   **Libraries:** Pandas, Scikit-learn, Seaborn, Matplotlib, Pickle.
*   **Environment:** Kaggle / Jupyter Notebook.

## 📂 Project Structure
```text
├── Crop_recommendation.csv       # The original dataset
├── crop_prediction_notebook.ipynb # Full analysis & training code
├── crop_rf_model.pkl             # The trained Random Forest model
├── label_encoder.pkl             # Dictionary to decode crop names
└── README.md                     # Project documentation
