# 🏠 House Price Prediction

A Machine Learning project that predicts house prices using regression techniques, built on the Boston Housing Dataset.

---

## 📌 Project Overview

This project explores how key housing features — such as number of rooms, population status, and pupil-teacher ratio — influence house prices. The primary model used is **Linear Regression**, with additional experiments using **Random Forest Regressor** and **Polynomial Regression** for performance comparison.

---

## 📂 Dataset

- **Source:** Boston Housing Dataset
- **Link:** [BostonHousing.csv](https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv)
- **Features Used:**
  | Feature | Description |
  |---------|-------------|
  | `rm` | Average number of rooms per dwelling |
  | `lstat` | % of lower-status population |
  | `ptratio` | Pupil-teacher ratio by town |
- **Target:** `medv` — Median value of owner-occupied homes (in $1000s)

---

## ⚙️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Model training & evaluation |
| Pickle | Model saving |
| Streamlit | (Planned) Web deployment |

---

## 🔍 Exploratory Data Analysis (EDA)

- **Scatter Plot** — Rooms (`rm`) vs Price (`medv`) relationship
- **Histogram** — Distribution of house prices
- **Heatmap** — Feature correlation analysis
- **Regression Plot** — `rm` vs `medv` trend visualization

---

## 🤖 Models Trained

| Model | R² Score |
|-------|----------|
| Linear Regression | **0.63** |
| Polynomial Regression (degree=2) | Higher |
| Random Forest Regressor | Higher |

> **Note:** Linear Regression was selected as the primary model per project requirements, despite other models achieving better R² scores. This demonstrates understanding of model selection trade-offs.

---

## 📊 Evaluation Metrics (Linear Regression)

- **MAE** — Mean Absolute Error
- **MSE** — Mean Squared Error
- **RMSE** — Root Mean Squared Error
- **R² Score** — 0.63

---

## 🧠 Key Learnings

- Feature selection and correlation analysis
- Data preprocessing with `StandardScaler`
- Comparing multiple regression algorithms
- Understanding trade-offs between model simplicity and accuracy
- Model persistence using `pickle`

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction

# 2. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn streamlit

# 3. Open the notebook
jupyter notebook house_Price_Pred__2_.ipynb
```

---

## 👤 Author

**Ahmad Ali**  
BS Computer Science — Lahore Leads University  
[LinkedIn](https://www.linkedin.com/in/ahmad-ali-117a8a264) | [GitHub](https://github.com/your-username)
