# 🤖 Machine Learning - Linear Regression

This repository contains linear regression implementations and learning materials for machine learning fundamentals.

## 📁 Repository Structure

```
Linear_Regression/
├── linearregression_day1.ipynb    # Basic linear regression tutorial
├── LR_day2.ipynb                  # Ice cream sales prediction
├── LR_day2_sal.ipynb             # Salary prediction model
├── LR_day2_stuPro.ipynb          # Student performance analysis
├── Salary_dataset.csv            # Salary dataset
├── Student_Performance.csv       # Student performance dataset
└── README.md                      # This file
```

## 📊 Featured Notebook: linearregression_day1.ipynb

### Overview
A comprehensive introduction to linear regression using scikit-learn, demonstrating the relationship between study hours and exam scores.

### Key Features
- **Perfect Linear Dataset**: Study hours (1-10) vs Exam scores (10-100)
- **Complete ML Pipeline**: Data preparation, model training, evaluation
- **Performance Metrics**: R², MSE, MAE analysis
- **Visualization**: Scatter plots for actual vs predicted values

### Learning Objectives
1. Understand linear regression fundamentals
2. Learn scikit-learn implementation
3. Master train-test split methodology
4. Interpret model coefficients and intercept
5. Evaluate model performance using multiple metrics

### Dataset Details
- **Features**: Study hours (independent variable)
- **Target**: Exam scores (dependent variable)
- **Relationship**: Perfect linear correlation (R² = 1.0)
- **Use Case**: Educational demonstration of linear regression concepts

### Code Highlights
```python
# Model Creation and Training
model = LinearRegression()
model.fit(x_train, y_train)

# Performance Evaluation
r2_score(y_test, y_pred)           # R² score
mean_squared_error(y_test, y_pred) # MSE
mean_absolute_error(y_test, y_pred) # MAE
```

## 🛠️ Technologies Used
- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **matplotlib** - Data visualization
- **scikit-learn** - Machine learning library
- **numpy** - Numerical computing

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas matplotlib scikit-learn numpy jupyter
```

### Running the Notebook
1. Clone this repository
2. Navigate to the Linear_Regression folder
3. Launch Jupyter Notebook: `jupyter notebook`
4. Open `linearregression_day1.ipynb`

## 📈 Model Performance
- **R² Score**: 1.0 (Perfect fit)
- **MSE**: ~0 (Minimal error)
- **MAE**: ~0 (Minimal absolute error)

## 🎯 Next Steps
- Explore real-world datasets with noise
- Implement multiple linear regression
- Study regularization techniques (Ridge, Lasso)
- Advanced evaluation metrics

## 👨‍💻 Author
**Rahullll101**

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

---
*Happy Learning! 🎓*
