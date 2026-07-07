# Yes Bank Stock Price Prediction

## Project Overview
This project predicts the closing stock price of Yes Bank using the Linear Regression algorithm. It includes data preprocessing, exploratory data analysis (EDA), feature selection, model building, prediction, and performance evaluation.

---

## Dataset
- **Dataset:** Yes Bank Stock Prices
- **Features:**
  - Date
  - Open
  - High
  - Low
- **Target Variable:**
  - Close

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

---

## Exploratory Data Analysis (EDA)
The following analyses were performed:
- Dataset Information
- Missing Value Analysis
- Duplicate Value Check
- Statistical Summary
- Correlation Heatmap
- Pairplot
- Scatter Plot
- Distribution Plot
- Box Plot

---

## Machine Learning Model
- Algorithm: **Linear Regression**
- Train-Test Split: **80:20**

---

## Model Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Results
The Linear Regression model achieved a high **R² Score (~0.99)**, indicating excellent prediction performance. The model successfully predicts the closing stock price with low prediction error.

---

## Project Structure

```
YesBank-Stock-Price-Prediction/
│
├── data_YesBank_StockPrices.csv
├── YesBank_EDA.ipynb
├── YB_Model.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YourGitHubUsername/YesBank-Stock-Price-Prediction.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Future Improvements
- Apply Feature Engineering.
- Compare Linear Regression with other regression models.
- Improve prediction accuracy through model tuning.
- Deploy the model using Flask or Streamlit.

---

## Author

**Simran**

- Diploma in Computer Engineering
- GitHub: https://github.com/simransimran20704-cloud
- LinkedIn: https://www.linkedin.com/in/simran-simran-6480ab306?utm_source=share_via&utm_content=profile&utm_medium=member_android

---

---

## Conclusion

This project demonstrates how Linear Regression can be used to predict Yes Bank's closing stock price using historical stock data. After performing data preprocessing, exploratory data analysis, feature selection, and model evaluation, the model achieved a high R² Score and low prediction error, making it effective for this dataset.
