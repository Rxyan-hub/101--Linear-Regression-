

![Python](https://img.shields.io/badge/python-ML-blue)

![Python](https://img.shields.io/badge/Linear-Regression-green)

# Linear Regression From Scratch  
A simple implementation of Linear Regression without using the scikit-learn library.  



## Features

- Predicts salary based on years of experience
- Linear regression implemented from scratch (no ML libraries)
- Step-by-step calculation of slope and intercept
- Easy to understand and modify for learning purposes
- Quick demo with sample data
## Usage/Examples

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

git clone https://github.com/Rxyan-hub/101--Linear-Regression-.git
cd 101--Linear-Regression-

2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Libraries to install 
pip install numpy pandas matplotlib

  

![Data Plot](https://github.com/user-attachments/assets/c6a89494-ce9d-47c9-b483-7f4a2d797748)

![Prediction Plot](https://github.com/user-attachments/assets/318a251c-8964-4ca4-ac75-87691b8f26b2)



