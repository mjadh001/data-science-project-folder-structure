# data-science-project-folder-structure
# Insurance Cost Prediction

This project uses a dataset of insurance policy holders to build a regression model that predicts medical expenses based on features like age, BMI, smoking status, and number of children.

## 📌 Objective

Build a machine learning model to predict medical insurance costs and explore relationships between features and expenses using Python and scikit-learn.

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset

- Source: [Kaggle Insurance Dataset](https://www.kaggle.com/mirichoi0218/insurance)
- Features:
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `expenses`

---

## 🧪 Steps

1. **Data Exploration** – Used histograms, pairplots, and correlation heatmaps.
2. **Preprocessing** – One-hot encoding, log transformations.
3. **Modeling** – Linear Regression, Ridge Regression.
4. **Evaluation** – RMSE, R², residual diagnostics.
5. **Interpretation** – Visualized coefficients and predictions.

---
## Learnings

- Feature scaling and encoding impact model performance.
- Log transformation helped in stabilizing variance.
- Smoking status is a dominant factor in cost prediction.

---

## 🚀 How to Run

```bash
# Set up virtual environment (optional)
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook notebooks/insurance_modeling.ipynb
