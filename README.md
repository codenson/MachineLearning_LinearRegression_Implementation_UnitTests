# Linear Regression Implementation

This project implements a simple linear regression model to predict profits based on population data. The implementation includes functions for computing cost, calculating gradients, and performing gradient descent to optimize the model parameters.

## Files

- **`main.py`**: The main script that loads the data, visualizes it, computes the cost, performs gradient descent, and makes predictions.
- **`utils.py`**: Contains utility functions for loading data.
- **`public_tests.py`**: Includes test cases to validate the correctness of the cost and gradient computation functions.
- **`data/ex1data1.txt`**: Dataset used for single-variable linear regression.
- **`data/ex1data2.txt`**: Dataset used for multi-variable linear regression (not used in `main.py`).

## Features

1. **Data Visualization**:
   - Scatter plot of profits vs. population.
   - Linear fit visualization after training.

2. **Cost Function**:
   - Computes the cost of using specific parameters for linear regression.

3. **Gradient Computation**:
   - Calculates the gradients of the cost function with respect to the model parameters.

4. **Gradient Descent**:
   - Optimizes the model parameters using batch gradient descent.

5. **Predictions**:
   - Predicts profits for given population sizes.

## How to Run

1. Ensure you have Python installed along with the required libraries:
   - `numpy`
   - `matplotlib`

2. Run the script:
   ```bash
   python main.py