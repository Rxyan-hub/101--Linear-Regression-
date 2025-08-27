## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

![Python](https://img.shields.io/badge/python-3.9%2B-blue)

![Python](https://img.shields.io/badge/python-ML-green)

# Linear Regression From Scratch  
A simple implementation of Linear Regression without using the scikit-learn library.  



## Features

- Predicts salary based on years of experience
- Linear regression implemented from scratch (no ML libraries)
- Step-by-step calculation of slope and intercept
- Easy to understand and modify for learning purposes
- Quick demo with sample data
## Usage/Examples

```python
from linear_regression import LinearRegressionModel

# Sample data: Years of experience and salary
X = [1, 2, 3, 4, 5]
y = [30000, 35000, 50000, 60000, 65000]

# Create and train the model
model = gradient_descent(X, y, L, iterations) 
model.fit(X, y)

# Predict salary for 6 years of experience
prediction = model.predict(6)
print(f"Predicted Salary: ${prediction}")

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Rxyan-hub/101--Linear-Regression-.git
cd 101--Linear-Regression-

2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Libraries to install 
pip install numpy pandas matplotlib

## Screenshots

## Screenshots  

![Data Plot](https://raw.githubusercontent.com/Rxyan-hub/101--Linear-Regression-/main/screenshot/Screenshot%202025-08-26%20024354.png)

![Prediction Plot](https://raw.githubusercontent.com/Rxyan-hub/101--Linear-Regression-/main/screenshot/Screenshot%202025-08-26%20023030.png)
