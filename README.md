## 📊 Project: Salary Prediction Using Linear Regression

This project uses a dataset of AI-related job listings to predict employee salaries (`salary_usd`) using features such as:

- Industry
- Company size
- AI adoption level
- Remote friendliness
- Required skills (one-hot encoded)

### 🔧 Steps Taken:
- Cleaned and standardized raw CSV data
- Encoded ordinal and categorical variables
- Split dataset into training and testing sets
- Trained a Linear Regression model
- Evaluated model using MAE and R²
- Exported predictions and visualized results

### 🧠 Results:
- **Mean Absolute Error (MAE):** ~$17,645
- **R² Score:** -0.021 (model did not generalize well — likely due to limited or synthetic data)
- Most predictions clustered around the mean salary regardless of job context

### 📈 Deliverables:
- `salary_predictions_linear.csv` (actual vs predicted salaries)
- `salary_predictions_scatter.png` (prediction visualization)

### 📚 Tools Used:
- Python (Pandas, Scikit-learn, Matplotlib)
- Jupyter Notebook
- Clean project structure (`data/`, `outputs/`, `models/`, `notebooks/`)

### ✅ Conclusion:
This basic linear regression pipeline is not optimized for accuracy, but it successfully demonstrates the end-to-end process of data cleaning, feature engineering, modeling, evaluation, and reporting — all of which are core skills for data analyst roles.
