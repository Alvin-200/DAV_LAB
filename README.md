<div align="center">

# 📊 Data Analysis & Visualization Lab

### 🏫 Chennai Institute of Technology — Semester 5

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![NumPy](https://img.shields.io/badge/NumPy-2.2.6-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.3.3-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10.3-11557C?style=for-the-badge)](https://matplotlib.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.6.1-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Lab_4.5.1-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)

---

> _A comprehensive collection of hands-on laboratory experiments exploring data analysis,  
> statistical inference, predictive modeling, hypothesis testing, and visualization using Python's scientific computing ecosystem._

</div>

---

## 🗂️ Repository Structure

```
DAV_LAB/
│
├── 📁 exp1/
│   ├── 📓 exp1.ipynb        ← Jupyter Notebook
│   └── 🐍 exp1.py           ← Python Script
│
├── 📁 exp2/
│   ├── 📓 exp2.ipynb        ← Jupyter Notebook (with outputs)
│   └── 🐍 exp2.py           ← Python Script
│
├── 📁 exp3/
│   ├── 📊 data.csv          ← Sample Dataset
│   ├── 📓 exp3.ipynb        ← Jupyter Notebook (with outputs)
│   └── 🐍 exp3.py           ← Python Script
│
├── 📁 exp4/
│   ├── 📊 Google_data (2b.c1).csv  ← Text/CSV Dataset
│   ├── 📊 data (2c2).xlsx          ← Excel Spreadsheet Dataset
│   ├── 📓 exp4.ipynb               ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp4.py                  ← Python Script
│   ├── 📄 processed_text.csv       ← Exported Processed CSV
│   └── 📄 processed_excel.xlsx     ← Exported Processed Excel
│
├── 📁 exp5/
│   ├── 📊 iris_dataset(2d).csv     ← Iris CSV Dataset
│   ├── 📓 exp5.ipynb               ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp5.py                  ← Python Script
│   ├── 🖼️ histograms.png            ← Feature Distributions Plot
│   ├── 🖼️ sepal_length_boxplot.png  ← Sepal Length Boxplot
│   └── 🖼️ pairplot.png              ← Feature Pairwise Scatter/KDE Plot
│
├── 📁 exp6/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp6.ipynb               ← Jupyter Notebook (with outputs)
│   └── 🐍 exp6.py                  ← Python Script
│
├── 📁 exp7/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp7.ipynb               ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp7.py                  ← Python Script
│   ├── 🖼️ uci_linear_regression.png ← UCI Linear Regression Scatter & Line Plot
│   └── 🖼️ pima_linear_regression.png ← Pima Linear Regression Scatter & Line Plot
│
├── 📁 exp8/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp8.ipynb               ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp8.py                  ← Python Script
│   ├── 🖼️ uci_multiple_regression.png  ← UCI Actual vs Predicted Scatter Plot
│   └── 🖼️ pima_multiple_regression.png ← Pima Actual vs Predicted Scatter Plot
│
├── 📁 exp9/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp9.ipynb               ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp9.py                  ← Python Script
│   └── 🖼️ model_comparison.png     ← Model Benchmark Comparative Bar Chart
│
├── 📁 exp10/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp10.ipynb              ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp10.py                 ← Python Script
│   ├── 🖼️ normal_curve_glucose.png   ← Fitted Normal PDF on Glucose
│   └── 🖼️ normal_curves_features.png ← Multi-Feature Fitted Normal Curves
│
├── 📁 exp11/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp11.ipynb              ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp11.py                 ← Python Script
│   └── 🖼️ z_test_plot.png          ← Standard Normal Distribution & Critical Z Thresholds
│
├── 📁 exp12/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp12.ipynb              ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp12.py                 ← Python Script
│   └── 🖼️ t_test_comparison.png    ← Independent Two-Sample T-Test Boxplots
│
├── 📁 exp13/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp13.ipynb              ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp13.py                 ← Python Script
│   └── 🖼️ anova_analysis.png       ← One-Way ANOVA Boxplot Across Age Groups
│
├── 📁 exp14/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp14.ipynb              ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp14.py                 ← Python Script
│   ├── 🖼️ linear_model_fit.png     ← Linear Model Regression Line Fit
│   └── 🖼️ residuals_plot.png       ← Residual Error vs Fitted Values & Distribution
│
├── 📁 exp15/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp15.ipynb              ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp15.py                 ← Python Script
│   ├── 🖼️ confusion_matrix.png     ← Classification Confusion Matrix Heatmap
│   └── 🖼️ roc_curve.png            ← Receiver Operating Characteristic (ROC) Curve
│
├── 📁 exp16/
│   ├── 📊 uci_diabetes.csv         ← UCI Diabetes Dataset
│   ├── 📊 pima_diabetes.csv        ← Pima Indians Diabetes Dataset
│   ├── 📓 exp16.ipynb              ← Jupyter Notebook (with outputs)
│   ├── 🐍 exp16.py                 ← Python Script
│   ├── 🖼️ time_series_decomposition.png ← Trend, Seasonal & Residual Decomposition
│   └── 🖼️ arima_forecast.png       ← ARIMA Multi-Step Forward Forecasting Plot
│
└── 📄 README.md
```

---

## 🧪 Experiments at a Glance

| # | Experiment | Description | Key Libraries |
|:-:|:-----------|:------------|:-------------:|
| 1 | **Environment Setup** | Verify installation & versions of essential data science packages | `numpy` `pandas` `matplotlib` `jupyter` |
| 2 | **NumPy Fundamentals** | Core array operations — creation, indexing, slicing, math, reshaping | `numpy` |
| 3 | **Pandas Data Analysis** | DataFrame manipulation — loading, cleaning, filtering, grouping, exporting | `pandas` |
| 4 | **Data Input/Output Operations** | Reading data from CSV, Excel, and Web; missing value treatment; exporting | `pandas` `openpyxl` |
| 5 | **Descriptive Analytics (Iris)** | Exploring statistics, distributions, boxplots, and pairplots on Iris dataset | `pandas` `seaborn` `matplotlib` |
| 6 | **Univariate Statistical Analysis** | Calculating Mean, Median, Mode, Variance, Std, Skewness, Kurtosis on Diabetes datasets | `pandas` `numpy` `scipy` |
| 7 | **Bivariate Analysis (Linear & Logistic Regression)** | Linear Regression (Glucose vs BMI) & Logistic Regression (Predicting Diabetes) | `pandas` `numpy` `scikit-learn` `matplotlib` |
| 8 | **Multiple Linear Regression Analysis** | Multiple independent variables (Glucose, BP, Age) predicting BMI with $R^2$ evaluation | `pandas` `numpy` `scikit-learn` `matplotlib` |
| 9 | **Comparative Analysis of Datasets** | Systematic comparison of statistical distributions & predictive models across cohorts | `pandas` `numpy` `scikit-learn` `matplotlib` |
| 10 | **Probability Distributions & Normal Curves** | Empirical distribution modeling & Gaussian PDF curve fitting on continuous features | `pandas` `numpy` `scipy` `matplotlib` `seaborn` |
| 11 | **Hypothesis Testing (One-Sample Z-Test)** | One-Sample Z-Test for Population Mean with standard normal rejection threshold plotting | `statsmodels` `scipy` `matplotlib` `pandas` |
| 12 | **Hypothesis Testing (Two-Sample T-Test)** | Independent two-sample Welch t-test comparing Diabetic vs Non-Diabetic groups | `scipy` `pandas` `matplotlib` `seaborn` |
| 13 | **Analysis of Variance (One-Way ANOVA)** | Evaluating statistical variance across age groups using One-Way ANOVA F-test | `scipy` `pandas` `matplotlib` `seaborn` |
| 14 | **Linear Model Error Diagnostics** | Comprehensive error metrics ($R^2$, MSE, RMSE, MAE) and residual distribution diagnostics | `scikit-learn` `pandas` `matplotlib` `seaborn` |
| 15 | **Classification Diagnostics (Logistic Regression)** | Confusion Matrix, Precision, Recall, F1-Score, and ROC-AUC curve diagnostics | `scikit-learn` `pandas` `matplotlib` `seaborn` |
| 16 | **Time Series Analysis & ARIMA Forecasting** | Seasonal decomposition (Trend, Seasonality, Residuals) and ARIMA time-series forecasting | `statsmodels` `pandas` `matplotlib` |

---

## 📝 Detailed Experiment Breakdown

<details>
<summary><strong>🔬 Experiment 1 — Environment Setup & Package Verification</strong></summary>

### 📌 Objective
Verify the installation and versions of all essential data science libraries required for the lab.

### 📦 Packages Checked

| Package | Status | Version |
|:--------|:------:|:-------:|
| NumPy | ✅ Installed | `2.2.6` |
| Pandas | ✅ Installed | `2.3.3` |
| Matplotlib | ✅ Installed | `3.10.3` |
| JupyterLab | ✅ Installed | `4.5.1` |
| Scikit-Learn | ✅ Installed | `1.6.1` |
| SciPy | ✅ Installed | `1.18.0` |
| Statsmodels | ✅ Installed | `0.14.6` |

### 📂 Files
- [`exp1/exp1.ipynb`](exp1/exp1.ipynb) — Jupyter Notebook
- [`exp1/exp1.py`](exp1/exp1.py) — Python Script

</details>

---

<details>
<summary><strong>🔬 Experiment 2 — Fundamentals of NumPy</strong></summary>

### 📌 Objective
Learn and demonstrate core NumPy operations for numerical computing.

### 🧩 Topics Covered

| Section | Topic | Key Functions |
|:-------:|:------|:-------------|
| 1 | Version Verification | `np.__version__` |
| 2 | Array Creation | `np.array()`, `np.ones()` |
| 3 | Indexing & Slicing | `arr[i]`, `arr[start:end]`, `arr[row, col]` |
| 4 | Element-wise Operations | `+`, `-`, `*`, `/`, scalar math |
| 5 | Statistical Aggregations | `np.sum()`, `np.mean()`, `np.std()` |
| 6 | Comparison & Masking | `>`, boolean indexing, fancy indexing |
| 7 | Reshaping & Structured Arrays | `.reshape()`, structured `dtype` |

### 📂 Files
- [`exp2/exp2.ipynb`](exp2/exp2.ipynb) — Jupyter Notebook (with cell outputs)
- [`exp2/exp2.py`](exp2/exp2.py) — Python Script

</details>

---

<details>
<summary><strong>🔬 Experiment 3 — Data Analysis & Manipulation using Pandas</strong></summary>

### 📌 Objective
Perform real-world data analysis workflows using Pandas DataFrames.

### 🧩 Topics Covered

| Section | Topic | Key Functions |
|:-------:|:------|:-------------|
| 1 | Load & Preview | `pd.read_csv()`, `.head()`, `.tail()` |
| 2 | Inspection | `.info()`, `.describe()` |
| 3 | Missing Values & Column Ops | `.fillna()`, column arithmetic |
| 4 | Filtering & Groupby | Boolean conditions, `.groupby().mean()` |
| 5 | Sorting & Boolean Masking | `.sort_values()`, `.median()` masking |
| 6 | Export & Aggregations | `.to_csv()`, `.sum()`, `.mean()`, `.std()` |

### 📂 Files
- [`exp3/exp3.ipynb`](exp3/exp3.ipynb) — Jupyter Notebook (with cell outputs)
- [`exp3/exp3.py`](exp3/exp3.py) — Python Script
- [`exp3/data.csv`](exp3/data.csv) — Sample Dataset

</details>

---

<details>
<summary><strong>🔬 Experiment 4 — Reading Data from Text Files, Excel, and the Web</strong></summary>

### 📌 Objective
Read and process data from various sources, including CSV text files, Excel spreadsheets, and web-based URLs using Pandas.

### 🧩 Topics Covered

| Section | Topic | Key Functions |
|:-------:|:------|:-------------|
| 1 | Read CSV / Text Data | `pd.read_csv('Google_data (2b.c1).csv')` |
| 2 | Read Excel Data | `pd.read_excel('data (2c2).xlsx', sheet_name='Sheet1')` |
| 3 | Read Web-Based Data | `pd.read_csv('https://raw.githubusercontent.com/...')` |
| 4 | Preview Datasets | `df.head()` |
| 5 | Handle Missing Values | `.ffill()`, `.bfill()`, `.dropna()` |
| 6 | Export Processed Data | `.to_csv('processed_text.csv')`, `.to_excel('processed_excel.xlsx')` |

### 📂 Files
- [`exp4/exp4.ipynb`](exp4/exp4.ipynb) — Jupyter Notebook (with cell outputs)
- [`exp4/exp4.py`](exp4/exp4.py) — Python Script
- [`exp4/Google_data (2b.c1).csv`](exp4/Google_data%20%282b.c1%29.csv) — CSV Dataset
- [`exp4/data (2c2).xlsx`](exp4/data%20%282c2%29.xlsx) — Excel Dataset
- [`exp4/processed_text.csv`](exp4/processed_text.csv) — Exported CSV Data
- [`exp4/processed_excel.xlsx`](exp4/processed_excel.xlsx) — Exported Excel Data

</details>

---

<details>
<summary><strong>🔬 Experiment 5 — Exploring Descriptive Analytics Using the Iris Dataset</strong></summary>

### 📌 Objective
Perform descriptive analytics, summary statistics, univariate, and bivariate visualizations on the Iris dataset using Pandas, Seaborn, and Matplotlib.

### 🧩 Topics Covered

| Section | Topic | Key Functions |
|:-------:|:------|:-------------|
| 1 | Dataset Load & Preview | `pd.read_csv('iris_dataset(2d).csv')` |
| 2 | Basic Info & Statistics | `df.info()`, `df.describe()` |
| 3 | Univariate Analysis | `df['species'].value_counts()` |
| 4 | Distribution Plots | `df.hist(figsize=(8, 6), edgecolor='black')` |
| 5 | Boxplot Analysis | `sns.boxplot(data=df, x='species', y='sepal length (cm)')` |
| 6 | Pair Plot Visualizations | `sns.pairplot(df, hue='species')` |

### 📂 Files
- [`exp5/exp5.ipynb`](exp5/exp5.ipynb) — Jupyter Notebook (with cell outputs)
- [`exp5/exp5.py`](exp5/exp5.py) — Python Script
- [`exp5/iris_dataset(2d).csv`](exp5/iris_dataset%282d%29.csv) — Iris Dataset
- [`exp5/histograms.png`](exp5/histograms.png) — Feature Distribution Plot
- [`exp5/sepal_length_boxplot.png`](exp5/sepal_length_boxplot.png) — Boxplot
- [`exp5/pairplot.png`](exp5/pairplot.png) — Pairwise Plot

</details>

---

<details>
<summary><strong>🔬 Experiment 6 — Statistical Analysis Using Diabetes Datasets (Univariate Analysis)</strong></summary>

### 📌 Objective
Perform univariate statistical analysis on the UCI Diabetes and Pima Indians Diabetes datasets to compute central tendency, dispersion, skewness, and kurtosis.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Import Datasets | `pd.read_csv('uci_diabetes.csv')`, `pd.read_csv('pima_diabetes.csv')` |
| 2 | Central Tendency | `np.mean()`, `np.median()`, `df[col].mode()[0]` |
| 3 | Dispersion | `np.var(ddof=1)`, `np.std(ddof=1)` |
| 4 | Shape & Tail Metrics | `scipy.stats.skew()`, `scipy.stats.kurtosis()` |
| 5 | Automated Pipeline | Custom function `univariate_analysis(df, columns)` |

### 📂 Files
- [`exp6/exp6.ipynb`](exp6/exp6.ipynb) — Jupyter Notebook (with cell outputs)
- [`exp6/exp6.py`](exp6/exp6.py) — Python Script
- [`exp6/uci_diabetes.csv`](exp6/uci_diabetes.csv) — UCI Diabetes Dataset
- [`exp6/pima_diabetes.csv`](exp6/pima_diabetes.csv) — Pima Indians Diabetes Dataset

</details>

---

<details>
<summary><strong>🔬 Experiment 7 — Bivariate Analysis: Linear and Logistic Regression Modeling</strong></summary>

### 📌 Objective
Perform bivariate analysis on the UCI Diabetes Dataset and Pima Indians Diabetes Dataset using Linear Regression (continuous vs. continuous) and Logistic Regression (binary classification of diabetes presence).

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Load Datasets | `pd.read_csv('uci_diabetes.csv')`, `pd.read_csv('pima_diabetes.csv')` |
| 2 | Linear Regression | `LinearRegression()`, `.fit()`, `.predict()`, `r2_score()` |
| 3 | Regression Visualizations | `plt.scatter()`, `plt.plot()`, regression line plotting |
| 4 | Logistic Regression | `train_test_split()`, `LogisticRegression()`, `accuracy_score()` |
| 5 | Performance Comparison | Evaluating model performance across dataset variations |

### 📂 Files
- [`exp7/exp7.ipynb`](exp7/exp7.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp7/exp7.py`](exp7/exp7.py) — Python Script
- [`exp7/uci_diabetes.csv`](exp7/uci_diabetes.csv) — UCI Diabetes Dataset
- [`exp7/pima_diabetes.csv`](exp7/pima_diabetes.csv) — Pima Indians Diabetes Dataset
- [`exp7/uci_linear_regression.png`](exp7/uci_linear_regression.png) — UCI Scatter Plot & Linear Fit
- [`exp7/pima_linear_regression.png`](exp7/pima_linear_regression.png) — Pima Scatter Plot & Linear Fit

</details>

---

<details>
<summary><strong>🔬 Experiment 8 — Multiple Linear Regression Analysis</strong></summary>

### 📌 Objective
Perform Multiple Linear Regression predicting a continuous target variable (`BMI`) using multiple independent predictor variables (`Glucose`, `BloodPressure`, and `Age`), and evaluate using $R^2$ score and regression diagnostics.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Feature Selection | Multidimensional feature matrix `['Glucose', 'BloodPressure', 'Age']` |
| 2 | Train-Test Split | `train_test_split(X, y, test_size=0.2, random_state=42)` |
| 3 | Model Training | `LinearRegression().fit(X_train, y_train)` |
| 4 | Coefficient Analysis | Intercept $\beta_0$ and feature coefficients $\beta_1, \beta_2, \beta_3$ |
| 5 | Evaluation & Plot | $R^2$ score calculation, Actual vs. Predicted scatter plot with reference fit line |

### 📂 Files
- [`exp8/exp8.ipynb`](exp8/exp8.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp8/exp8.py`](exp8/exp8.py) — Python Script
- [`exp8/uci_diabetes.csv`](exp8/uci_diabetes.csv) — UCI Diabetes Dataset
- [`exp8/pima_diabetes.csv`](exp8/pima_diabetes.csv) — Pima Indians Diabetes Dataset
- [`exp8/uci_multiple_regression.png`](exp8/uci_multiple_regression.png) — UCI Actual vs Predicted Plot
- [`exp8/pima_multiple_regression.png`](exp8/pima_multiple_regression.png) — Pima Actual vs Predicted Plot

</details>

---

<details>
<summary><strong>🔬 Experiment 9 — Comparative Analysis of Statistical & Predictive Models</strong></summary>

### 📌 Objective
Conduct a cross-dataset benchmarking study comparing univariate statistical metrics and predictive model efficacy (Linear vs. Logistic Regression) across dataset variants.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Summary Statistics | `.describe().T` on all numerical features |
| 2 | Linear Regression Benchmark | Comparative $R^2$ evaluation on continuous feature predictions |
| 3 | Classification Benchmark | Comparative classification Accuracy score on diabetes prediction |
| 4 | Visualization | Dual-panel comparative bar charts for $R^2$ and Accuracy |

### 📂 Files
- [`exp9/exp9.ipynb`](exp9/exp9.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp9/exp9.py`](exp9/exp9.py) — Python Script
- [`exp9/uci_diabetes.csv`](exp9/uci_diabetes.csv) — UCI Diabetes Dataset
- [`exp9/pima_diabetes.csv`](exp9/pima_diabetes.csv) — Pima Indians Diabetes Dataset
- [`exp9/model_comparison.png`](exp9/model_comparison.png) — Comparative Model Benchmark Chart

</details>

---

<details>
<summary><strong>🔬 Experiment 10 — Probability Distributions & Normal Curve Fitting</strong></summary>

### 📌 Objective
Fit theoretical Normal (Gaussian) Probability Density Function (PDF) curves over continuous health distributions to analyze empirical normality.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Parametric Estimation | Calculating sample mean $\mu$ and standard deviation $\sigma$ |
| 2 | Normal PDF Modeling | `scipy.stats.norm.pdf(x, mu, std)` |
| 3 | Density Histograms | `sns.histplot(stat='density', kde=True)` |
| 4 | Multi-Feature Diagnostics | Multi-panel grid comparing Glucose, BloodPressure, BMI, and Age |

### 📂 Files
- [`exp10/exp10.ipynb`](exp10/exp10.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp10/exp10.py`](exp10/exp10.py) — Python Script
- [`exp10/uci_diabetes.csv`](exp10/uci_diabetes.csv) — UCI Diabetes Dataset
- [`exp10/normal_curve_glucose.png`](exp10/normal_curve_glucose.png) — Glucose Normal Curve Fit
- [`exp10/normal_curves_features.png`](exp10/normal_curves_features.png) — Multi-Feature Normal Curves

</details>

---

<details>
<summary><strong>🔬 Experiment 11 — Hypothesis Testing: One-Sample Z-Test</strong></summary>

### 📌 Objective
Conduct a formal One-Sample Z-Test testing if sample mean Glucose differs significantly from a hypothesized population mean ($\mu_0 = 100$) and map critical rejection thresholds.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Hypothesis Formulation | $H_0: \mu = 100$ vs. $H_1: \mu \neq 100$ |
| 2 | Z-Test Execution | `statsmodels.stats.weightstats.ztest(df['Glucose'], value=100)` |
| 3 | Critical Values | Calculating two-tailed rejection thresholds ($Z_{\text{crit}} = \pm 1.96$) |
| 4 | Rejection Region Mapping | Visualizing Gaussian bell curve with shaded critical rejection regions |

### 📂 Files
- [`exp11/exp11.ipynb`](exp11/exp11.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp11/exp11.py`](exp11/exp11.py) — Python Script
- [`exp11/uci_diabetes.csv`](exp11/uci_diabetes.csv) — UCI Diabetes Dataset
- [`exp11/z_test_plot.png`](exp11/z_test_plot.png) — Z-Test Standard Normal Rejection Plot

</details>

---

<details>
<summary><strong>🔬 Experiment 12 — Hypothesis Testing: Independent Two-Sample T-Test</strong></summary>

### 📌 Objective
Execute Independent Two-Sample T-Tests (Welch's t-test) to test for statistically significant mean differences between Diabetic and Non-Diabetic patient cohorts.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Cohort Partitioning | Subsetting data by class label (`Outcome = 0` vs `Outcome = 1`) |
| 2 | T-Test Execution | `scipy.stats.ttest_ind(group0, group1, equal_var=False)` |
| 3 | Hypothesis Interpretation | Analyzing t-statistic and p-value against $\alpha = 0.05$ |
| 4 | Visual Distribution Plots | Two-sample comparative boxplots across datasets |

### 📂 Files
- [`exp12/exp12.ipynb`](exp12/exp12.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp12/exp12.py`](exp12/exp12.py) — Python Script
- [`exp12/uci_diabetes.csv`](exp12/uci_diabetes.csv) — UCI Diabetes Dataset
- [`exp12/pima_diabetes.csv`](exp12/pima_diabetes.csv) — Pima Indians Diabetes Dataset
- [`exp12/t_test_comparison.png`](exp12/t_test_comparison.png) — T-Test Group Comparison Boxplot

</details>

---

<details>
<summary><strong>🔬 Experiment 13 — Analysis of Variance (One-Way ANOVA)</strong></summary>

### 📌 Objective
Perform One-Way ANOVA across multiple categorical age brackets to evaluate between-group versus within-group variance.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Demographic Binning | Categorizing Age into Young (20-30), Middle-Aged (31-50), and Senior (51+) |
| 2 | ANOVA Test | `scipy.stats.f_oneway(*groups)` |
| 3 | Variance Analysis | Computing F-statistic and assessing statistical significance |
| 4 | Visualization | Cohort-level boxplots across demographic tiers |

### 📂 Files
- [`exp13/exp13.ipynb`](exp13/exp13.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp13/exp13.py`](exp13/exp13.py) — Python Script
- [`exp13/uci_diabetes.csv`](exp13/uci_diabetes.csv) — UCI Diabetes Dataset
- [`exp13/pima_diabetes.csv`](exp13/pima_diabetes.csv) — Pima Indians Diabetes Dataset
- [`exp13/anova_analysis.png`](exp13/anova_analysis.png) — One-Way ANOVA Boxplot Plot

</details>

---

<details>
<summary><strong>🔬 Experiment 14 — Linear Regression Diagnostics & Error Metrics</strong></summary>

### 📌 Objective
Perform comprehensive regression diagnostics calculating $R^2$, MSE, RMSE, MAE, and evaluating residual error distributions for model validation.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Model Fitting | `LinearRegression().fit(X_train, y_train)` |
| 2 | Error Metrics | `mean_squared_error`, `mean_absolute_error`, `np.sqrt(MSE)` |
| 3 | Residual Diagnostics | Calculating residual errors $e_i = y_i - \hat{y}_i$ |
| 4 | Diagnostic Plots | Residuals vs Fitted values scatter plot and Residual Error Distribution KDE |

### 📂 Files
- [`exp14/exp14.ipynb`](exp14/exp14.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp14/exp14.py`](exp14/exp14.py) — Python Script
- [`exp14/pima_diabetes.csv`](exp14/pima_diabetes.csv) — Pima Indians Diabetes Dataset
- [`exp14/linear_model_fit.png`](exp14/linear_model_fit.png) — Model Regression Fit Plot
- [`exp14/residuals_plot.png`](exp14/residuals_plot.png) — Residual Diagnostics Plots

</details>

---

<details>
<summary><strong>🔬 Experiment 15 — Classification Diagnostics & Logistic Regression</strong></summary>

### 📌 Objective
Train and evaluate a Logistic Regression classification model using a comprehensive diagnostic suite including Confusion Matrix, Precision, Recall, F1-Score, and ROC-AUC curve.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Classification Training | `LogisticRegression(max_iter=1000).fit(X_train, y_train)` |
| 2 | Diagnostic Metrics | `accuracy_score`, `precision_score`, `recall_score`, `f1_score` |
| 3 | Confusion Matrix | `confusion_matrix(y_test, y_pred)` with heatmap visualization |
| 4 | ROC-AUC Curve | `roc_curve`, `auc`, and Receiver Operating Characteristic curve plotting |

### 📂 Files
- [`exp15/exp15.ipynb`](exp15/exp15.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp15/exp15.py`](exp15/exp15.py) — Python Script
- [`exp15/pima_diabetes.csv`](exp15/pima_diabetes.csv) — Pima Indians Diabetes Dataset
- [`exp15/confusion_matrix.png`](exp15/confusion_matrix.png) — Confusion Matrix Heatmap
- [`exp15/roc_curve.png`](exp15/roc_curve.png) — ROC-AUC Diagnostic Curve

</details>

---

<details>
<summary><strong>🔬 Experiment 16 — Time Series Decomposition & ARIMA Forecasting</strong></summary>

### 📌 Objective
Perform temporal analysis on sequential patient records, decomposing underlying trend and seasonal patterns and training an ARIMA model for forward health forecasting.

### 🧩 Topics Covered

| Section | Topic | Key Functions / Metrics |
|:-------:|:------|:-----------------------|
| 1 | Time Series Structuring | Generating date indices and constructing pandas time series |
| 2 | Classical Decomposition | `seasonal_decompose(model='additive', period=7)` |
| 3 | ARIMA Modeling | `ARIMA(train, order=(1, 1, 1)).fit()` |
| 4 | Forward Forecasting | Multi-step forecasting against hold-out test sequence |

### 📂 Files
- [`exp16/exp16.ipynb`](exp16/exp16.ipynb) — Jupyter Notebook (with cell outputs & plots)
- [`exp16/exp16.py`](exp16/exp16.py) — Python Script
- [`exp16/pima_diabetes.csv`](exp16/pima_diabetes.csv) — Pima Indians Diabetes Dataset
- [`exp16/time_series_decomposition.png`](exp16/time_series_decomposition.png) — 4-Panel Decomposition Plot
- [`exp16/arima_forecast.png`](exp16/arima_forecast.png) — ARIMA Forward Forecast Plot

</details>

---

## 🚀 Getting Started

### Prerequisites

```bash
# Ensure Python 3.x is installed
python --version

# Install required packages
pip install numpy pandas matplotlib seaborn scipy scikit-learn statsmodels jupyterlab openpyxl
```

### Running Notebooks

```bash
# Clone the repository
git clone https://github.com/ALVIN-200
/DAV_LAB.git
cd DAV_LAB

# Launch Jupyter Lab
jupyter lab
```

### Running Python Scripts

```bash
# Example: Run Experiment 8 (Multiple Linear Regression)
cd exp8
python exp8.py

# Example: Run Experiment 15 (Logistic Regression Diagnostics)
cd ../exp15
python exp15.py
```

---

## 🛠️ Tech Stack

<div align="center">

| Technology | Purpose |
|:----------:|:--------|
| 🐍 **Python 3.x** | Core programming language |
| 🔢 **NumPy** | Numerical computing & array operations |
| 🐼 **Pandas** | Data manipulation & analysis |
| 📈 **Matplotlib** | Data visualization & plotting |
| 📊 **Seaborn** | Statistical graphics & distributions |
| 🤖 **Scikit-Learn** | Machine learning & predictive modeling |
| 📐 **SciPy & Statsmodels** | Advanced hypothesis testing & time series |
| 📓 **Jupyter Lab** | Interactive notebook environment |

</div>

---

## 📊 Learning Roadmap

```
 ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
 │   Exp 1-4    │     │   Exp 5-7    │     │   Exp 8-16   │
 │ Fundamentals │────▶│ Descriptive  │────▶│ Advanced ML, │
 │  & I/O Ops   │     │ & Regression │     │Stats & Series│
 └──────────────┘     └──────────────┘     └──────────────┘
```

> [!NOTE]
> Each experiment builds upon concepts from the previous one. It is recommended to follow the experiments in order from 1 to 16.

> [!TIP]
> All notebooks include pre-rendered cell outputs and high-resolution visualizations so you can review results without needing to re-run execution cells.

---

<div align="center">

### ⭐ Star this repo if you found it helpful!

Made with ❤️ for **Data Analysis & Visualization Lab**

</div>