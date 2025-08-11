# Linear Regression with Normal Equation

An implementation of linear regression using vectorized operations with NumPy. This project shows how to build linear regression from scratch using normal equation.

## 🚀 Features

- **Fully Vectorized**: No Python loops - all operations use NumPy's optimized C implementations
- **Mathematical Foundation**: Implements the normal equation method for exact solutions
- **Validation**: Includes sklearn comparison to verify correctness
- **Performance Metrics**: Calculates R², MSE, RMSE, and other regression metrics

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/fatihsko/linear_regression_vectorized.git
cd vectorized-linear-regression

# Install required dependencies
pip install numpy matplotlib scikit-learn
```

## 🔬 Mathematical Background

This implementation uses the **Normal Equation** method to find optimal parameters:

```
β = (X'X)⁻¹X'y
```

Where:
- `β` = parameter vector [intercept, slope]
- `X` = design matrix with column of ones for intercept
- `y` = target values
  
- If you want to understand what a normal equation is and the mathematical depths of the formulas in the code, I recommend you to read this:
  [Linear Algebra Review](https://cs229.stanford.edu/main_notes.pdf) Chapter 1, Section 2

## 📚 Educational Value

This implementation demonstrates:

- **Linear Algebra**: Matrix operations in machine learning
- **Vectorization**: Writing efficient numerical code
- **Statistical Metrics**: R-squared, MSE, residual analysis
- **Data Visualization**: Plotting regression results
- **Code Organization**: Clean, modular class design


## 📋 Requirements

```
numpy>=1.20.0
matplotlib>=3.3.0
scikit-learn>=1.0.0
```
  
## 🔍 Example Results

<img width="876" height="552" alt="plot_picture" src="https://github.com/user-attachments/assets/9d1dec9e-137f-4efe-b5da-e6b97c249202" />

*Sample output showing the fitted regression line with R² = 0.967*

---

⭐ **Star this repository** if you found it helpful for learning linear regression!

🐛 **Found a bug?** Please open an issue with details.

💡 **Have suggestions?** I'd love to hear your ideas for improvements!
