# 🌾 Agriculture Crop Prediction using Machine Learning

## 📌 Project Overview

This project predicts **agricultural crop yield (Quintal/Hectare)** using Machine Learning. A **Random Forest Regressor** is trained on historical agricultural data to estimate crop yield based on cultivation cost, production cost, crop type, and state.

The objective is to assist farmers, researchers, and policymakers in making informed agricultural decisions using data-driven predictions.

---

## 🚀 Features

- Data preprocessing and cleaning
- Label Encoding for categorical features
- Train-Test Split
- Random Forest Regression model
- Model evaluation using MAE, MSE, and R² Score
- Feature Importance Analysis
- Data visualization using Matplotlib

---

## 📂 Dataset

The dataset contains the following features:

| Feature | Description |
|---------|-------------|
| Crop | Type of crop |
| State | State where the crop is cultivated |
| Cost of Cultivation (A2+FL) | Cost of cultivation per hectare |
| Cost of Cultivation (C2) | Comprehensive cultivation cost |
| Cost of Production (C2) | Production cost per quintal |
| Yield (Quintal/Hectare) | Target variable |

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🤖 Machine Learning Algorithm

**Random Forest Regressor**

Why Random Forest?

- Handles nonlinear relationships
- High prediction accuracy
- Reduces overfitting
- Provides feature importance

---

## 📊 Model Performance

| Metric | Value |
|---------|--------|
| Mean Absolute Error (MAE) | **28.44** |
| Mean Squared Error (MSE) | **4852.74** |
| R² Score | **0.9463** |

The model achieved an **R² Score of 94.63%**, indicating excellent predictive performance.

---

## 📈 Workflow

1. Import Libraries
2. Load Dataset
3. Explore Data
4. Data Preprocessing
5. Feature Encoding
6. Split Dataset
7. Train Random Forest Model
8. Make Predictions
9. Evaluate Model
10. Visualize Feature Importance

---

## 📷 Output

The project generates:

- Predicted Crop Yield
- Model Performance Metrics
- Feature Importance Graph

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/hithaishi13/upskillcampus_Agriculture_Crop_Prediction.git
```

### Navigate to the project

```bash
cd upskillcampus_Agriculture_Crop_Prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Agriculture_Crop_Prediction.ipynb
```

Run all cells.

---

## 📁 Project Structure

```
Agriculture_Crop_Prediction/
│
├── Agriculture_Crop_Prediction.ipynb
├── datafile (1).csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🎯 Future Improvements

- Hyperparameter tuning
- Compare multiple regression algorithms
- Deploy using Streamlit or Flask
- Add more agricultural datasets
- Real-time crop yield prediction

---

## 👨‍💻 Author

**Hithaishi S H**

Computer Science & Engineering Student

GitHub:
https://github.com/hithaishi13

---

## 📜 License

This project is developed for educational and internship purposes.
