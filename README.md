
# ⚽ Football Match Events Analysis

This Jupyter Notebook explores and analyzes football match event data using pandas, seaborn, and scikit-learn. The goal is to clean, preprocess, and gain insights from a dataset containing match events, potentially to be used for predictive modeling or exploratory data analysis.

---

## 📁 Dataset

- `events.csv`: Contains raw data of football match events.
- `dictionary.txt`: Used to decode categorical values (e.g., event types, outcomes).

---

## 📊 Key Features

- Data cleaning and preprocessing:
  - Removal of irrelevant columns
  - Interpolation of missing values
  - Categorical encoding
- Feature scaling using:
  - `StandardScaler`
  - `MinMaxScaler`
- Exploratory Data Analysis (EDA) using visualizations

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📌 How to Use

1. Place `events.csv` and `dictionary.txt` in the same directory as the notebook.
2. Open the notebook using Jupyter:
```bash
jupyter notebook footballmatch.ipynb
```
3. Run the cells to preprocess data, visualize, and explore features.

---

## 📈 Potential Extensions

- Feature engineering for modeling goals, assists, or fouls.
- Predictive modeling (e.g., match outcome, player performance).
- Real-time event stream analysis (with live data feeds).


