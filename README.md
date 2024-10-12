# Gradient Descent and Optimization Visualizations

This project provides an interactive visualization of different gradient descent optimization techniques (Standard Gradient Descent, RMSProp, Momentum, and Adam) applied to a non-trivial mathematical function.

## Features

- **Function Visualization**: Plots a complex function `f(x) = sin(5 * x) + (x ** 2) / 10` that has sharp valleys and flat regions.
- **Gradient Descent**: Demonstrates standard gradient descent optimization.
- **Advanced Optimizers**: Visualizes how RMSProp, Momentum, and Adam optimizers perform on the same function.
- **Animations**: Animates the steps taken by the optimizers, helping to understand the convergence of different methods.

## Requirements

- Python 3.10 or later
- NumPy
- Matplotlib
- Seaborn
- Pillow (for saving animations)

## How to Run

1. Install the required libraries:
    ```bash
    pip install numpy matplotlib seaborn pillow
    ```

2. Run the notebook to visualize the optimization steps.

## Output

- The notebook generates animations showing how each optimizer converges to a minimum on the function.
- Example output:
  - **Gradient Descent**: `gradient_descent.gif`
  - **RMSProp**: `gradient_descent_RMSPROP.gif`
  - **Adam**: `adam_optimizer.gif`

## Credits

- Developed with the goal of visually demonstrating the effectiveness of different optimizers for machine learning tasks.
