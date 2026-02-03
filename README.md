# Linear Regression From Scratch

A complete implementation of Linear Regression from scratch using Python and NumPy, without using scikit-learn's LinearRegression model.

## Overview

This project demonstrates how linear regression works under the hood by implementing the algorithm from first principles. It includes:

- **Mathematical Foundation**: Understanding the theory behind linear regression
- **Gradient Descent**: Implementation of the optimization algorithm
- **Cost Function**: Mean Squared Error (MSE) calculation
- **Visualization**: Plotting the regression line and cost function convergence
- **Model Evaluation**: R² score and prediction analysis

## Features

- ✅ Linear regression implementation using only NumPy
- ✅ Gradient descent optimization
- ✅ Cost function tracking and visualization
- ✅ Training on real-world datasets
- ✅ Model evaluation metrics
- ✅ Interactive visualizations with matplotlib

## Mathematical Background

Linear regression finds the best-fitting line through data points by minimizing the cost function:

**Hypothesis**: `h(x) = θ₀ + θ₁x`

**Cost Function (MSE)**: `J(θ) = (1/2m) Σ(h(x⁽ⁱ⁾) - y⁽ⁱ⁾)²`

**Gradient Descent Update**:
- `θ₀ := θ₀ - α × (1/m) Σ(h(x⁽ⁱ⁾) - y⁽ⁱ⁾)`
- `θ₁ := θ₁ - α × (1/m) Σ(h(x⁽ⁱ⁾) - y⁽ⁱ⁾) × x⁽ⁱ⁾`

Where:
- `m` = number of training examples
- `α` = learning rate
- `θ₀` = bias term (intercept)
- `θ₁` = weight (slope)

## Installation

1. Clone or download this repository
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Open and run the Jupyter notebook:

```bash
jupyter notebook Linear_Regression_From_Scratch.ipynb
```

The notebook contains:
1. Data generation and preprocessing
2. Linear regression class implementation
3. Model training with gradient descent
4. Visualization of results
5. Model evaluation

## Requirements

- Python 3.7+
- NumPy
- Matplotlib
- Jupyter Notebook

See `requirements.txt` for specific versions.

## Project Structure

```
Linear regression/
├── Linear_Regression_From_Scratch.ipynb  # Main implementation notebook
├── README.md                              # Project documentation
└── requirements.txt                       # Python dependencies
```

## Results

The implementation includes:
- **Training visualization**: See how the regression line fits the data
- **Cost convergence**: Track how the cost function decreases over iterations
- **Performance metrics**: R² score and prediction accuracy
- **Comparison**: Results comparable to scikit-learn's implementation

## Learning Outcomes

By working through this project, you'll understand:
- How linear regression works mathematically
- The role of gradient descent in optimization
- How to implement ML algorithms from scratch
- The importance of learning rate and iterations
- Model evaluation techniques

