# California Housing Price Prediction

## 📌 Project Overview

This project uses Machine Learning regression algorithms to predict median house values in California based on housing-related features.

The project compares three regression models: Ordinary Least Squares (OLS), Ridge Regression, and Lasso Regression to evaluate their performance.

## 🎯 Objectives

* Analyze the California Housing dataset.
* Handle missing values in the dataset.
* Perform feature engineering to improve model performance.
* Analyze correlations between numerical features.
* Train and compare OLS, Ridge, and Lasso regression models.
* Tune Ridge and Lasso hyperparameters using GridSearchCV.
* Evaluate models using RMSE, MAE, and R² score.
* Visualize actual vs. predicted values and residuals.

## 📂 Dataset

**Dataset:** California Housing Dataset

The dataset contains housing information, including:

* `longitude` — Geographic longitude.
* `latitude` — Geographic latitude.
* `housing_median_age` — Median age of houses.
* `total_rooms` — Total rooms in the area.
* `total_bedrooms` — Total bedrooms in the area.
* `population` — Population of the area.
* `households` — Number of households.
* `median_income` — Median income.
* `median_house_value` — Target variable to predict.
* `ocean_proximity` — Proximity to the ocean.

**Dataset source:** [California Housing CSV](https://raw.githubusercontent.com/ageron/handson-ml2/master/datasets/housing/housing.csv)

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## ⚙️ Project Workflow

1. Load and explore the dataset.
2. Check and handle missing values.
3. Perform feature engineering by creating ratio and interaction features.
4. Visualize feature correlations using a heatmap.
5. Split the dataset into training and testing sets.
6. Apply numerical imputation, categorical encoding, and feature scaling.
7. Train OLS, Ridge, and Lasso regression models.
8. Tune Ridge and Lasso using GridSearchCV.
9. Compare model performance using RMSE, MAE, and R².
10. Visualize predictions and residuals.
11. Summarize the results and identify the best-performing model.

## 🤖 Machine Learning Models

### 1. OLS Regression

Ordinary Least Squares regression is used as the baseline model to predict median house values.

### 2. Ridge Regression

Ridge regression uses L2 regularization to reduce the impact of large coefficients and help control overfitting.

### 3. Lasso Regression

Lasso regression uses L1 regularization and can reduce some feature coefficients to zero.

## 📊 Evaluation Metrics

The models are evaluated using the following metrics:

* **RMSE:** Measures the square root of the average squared prediction error. Lower is better.
* **MAE:** Measures the average absolute prediction error. Lower is better.
* **R² Score:** Measures how much variation in the target variable is explained by the model. Higher is generally better.

## 📈 Visualizations

The notebook includes:

* Correlation heatmap.
* Actual vs. predicted house values.
* Residual distribution plots.
* Residuals vs. predicted values.

## 🚀 How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/california-housing-regression.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 2: Open the Project Folder

```bash
cd california-housing-regression
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Notebook

Open `california_housing_regression_comparison.ipynb` and run all cells from top to bottom.

**Note:** An internet connection is required to download the dataset from the source URL.

## 🏆 Results

The notebook compares OLS, Ridge, and Lasso regression using RMSE, MAE, and R² scores.

The best-performing model should be selected based on the evaluation results produced when the notebook is executed.

## 🔮 Future Improvements

* Experiment with additional regression algorithms.
* Use cross-validation for more robust evaluation.
* Improve feature engineering.
* Develop a simple web application for house value prediction.
* Deploy the trained model as an API.

## 👨‍💻 Author

**Your Name**

GitHub: [Your GitHub Profile](https://github.com/YOUR-USERNAME)

---

⭐ If you find this project useful, consider giving the repository a star.
