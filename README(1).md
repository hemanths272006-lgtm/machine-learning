# 🏠 Boston House Price Prediction — Machine Learning

A beginner-friendly **Machine Learning project** that explores the Boston Housing dataset and builds Linear Regression models to predict house prices.

## 📌 Project Overview

This project demonstrates a complete basic Machine Learning workflow:

- Loading a dataset from GitHub
- Exploratory Data Analysis (EDA)
- Feature distribution visualization
- Scatter plots
- Outlier visualization using boxplots
- Correlation analysis using a heatmap
- Simple Linear Regression (SLR)
- Multiple Linear Regression (MLR)
- Model prediction
- R² evaluation
- OLS statistical analysis

## 🧠 Machine Learning

This repository is primarily a **Machine Learning / Data Science project**, not a Generative AI project.

The main ML algorithms used are:

### 1. Simple Linear Regression
Uses the `rm` feature (average number of rooms) to predict `medv` (house price).

### 2. Multiple Linear Regression
Uses multiple features:

- `rm` — average number of rooms
- `lstat` — lower status population percentage
- `ptratio` — pupil-teacher ratio

to predict:

- `medv` — median house value

The models are trained using `scikit-learn`.

## 📊 Dataset

The project uses the **Boston Housing dataset**, loaded directly from:

`https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv`

The dataset contains housing-related features and the target variable `medv`.

## 🔄 Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
EDA & Visualization
   ↓
Correlation Analysis
   ↓
Train/Test Split
   ↓
Simple Linear Regression
   ↓
Multiple Linear Regression
   ↓
Predictions
   ↓
R² Evaluation
   ↓
OLS Statistical Analysis
```

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Google Colab / Jupyter Notebook

## 📁 Project Structure

```text
Boston-House-Price-ML/
│
├── ML(2).ipynb
├── ml(2).py
├── EDA_ipyn(1).ipynb
└── README.md
```

## 🚀 How to Run

### Option 1 — Google Colab

1. Open `ML(2).ipynb` in Google Colab.
2. Run the cells from top to bottom.
3. The dataset is automatically loaded from GitHub.

### Option 2 — Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

Then start Jupyter:

```bash
jupyter notebook
```

Open `ML(2).ipynb` and run the notebook.

### Option 3 — Python

Run:

```bash
python ml(2).py
```

## 📈 Model Evaluation

The project evaluates predictions using the **R² (R-squared)** score.

The notebook also creates a comparison between actual and predicted house prices and displays model coefficients.

## 📚 What I Learned

Through this project, I practiced:

- Understanding a structured dataset
- Performing EDA
- Visualizing relationships between variables
- Splitting data into training and testing sets
- Training regression models
- Making predictions
- Evaluating model performance
- Understanding regression coefficients
- Using OLS for statistical analysis

## 🔮 Future Improvements

Possible improvements include:

- Feature scaling
- Trying Random Forest and Decision Tree Regression
- Comparing multiple ML algorithms
- Hyperparameter tuning
- Cross-validation
- More detailed error analysis
- Building a Streamlit web application for predictions

## 👨‍💻 Author

**Hemanth S**

BE Computer Science & Engineering (AI & ML)

---

⭐ If you find this project useful, consider giving the repository a star!
