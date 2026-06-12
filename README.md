# AI-Powered-Investment-Intelligence-Platform
## Environment Setup

### Prerequisites

Ensure the following software is installed:

* Python 3.10 or later
* Jupyter Notebook or Google Colab
* Git (optional)

### Clone the Repository

```bash
git clone https://github.com/thannujyadav85/AI-Powered-Investment-Intelligence-Platform.git
cd AI-Powered-Investment-Intelligence-Platform
```

---

## Dependency Installation

Install all required libraries using:

```bash
pip install -r requirements.txt
```

Required libraries include:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* xgboost
* shap
* gradio

---

## Running the Application

### Option 1: Google Colab (Recommended)

1. Upload the notebook:

   * `Investment_Intelligence.ipynb`

2. Upload the dataset ZIP files to Google Drive.

3. Update dataset paths if required.

4. Run all notebook cells sequentially.

### Option 2: Jupyter Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Investment_Intelligence.ipynb
```

Run all cells from top to bottom.

---

## Reproducing Results

To reproduce the project outputs:

### Step 1: Load Dataset

* Extract Dataset 1 and Dataset 2.
* Mount Google Drive if using Colab.

### Step 2: Run Data Preparation

* Data loading
* Data cleaning
* Symbol mapping
* Industry mapping

### Step 3: Run Feature Engineering

Generate:

* Moving Averages
* Exponential Moving Averages
* RSI
* MACD
* Bollinger Bands
* Volatility Features
* Return Features
* Volume Features

### Step 4: Train Models

Run:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier
* Random Forest Regressor
* XGBoost Regressor

### Step 5: Portfolio Optimization

Generate:

* Conservative Portfolio
* Balanced Portfolio
* Aggressive Portfolio

using Monte Carlo simulation.

### Step 6: Explainability and Anomaly Detection

Generate:

* SHAP Feature Importance
* SHAP Summary Analysis
* Return Anomalies
* Volume Anomalies
* Volatility Anomalies

### Step 7: Export Results

The notebook produces:

* ranking_df.csv
* stock_summary.csv
* portfolio_profiles.csv
* forecast_comparison.csv
* latest_recommendations.csv
* conservative_alloc.csv
* balanced_alloc.csv
* aggressive_alloc.csv
* return_anomalies.csv
* volume_anomalies.csv

These files are included in the repository.
