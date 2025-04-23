# Machine Learning Implementations

This repository contains various machine learning algorithms implemented from scratch. Each implementation is designed to be educational and easy to understand, with a focus on the fundamental concepts.

## Gradient Descent Implementation

The current implementation focuses on gradient descent for linear regression, including:

### Key Components

- **Cost Function**: Computes the mean squared error between predictions and actual values
- **Gradient Function**: Calculates the gradients of the cost function with respect to parameters w and b
- **Gradient Descent Algorithm**: Implements the iterative process of updating parameters to minimize cost

### Features

- Implements univariate linear regression
- Includes visualization tools for cost contours and gradient descent paths
- Demonstrates the impact of learning rate on convergence
- Provides clear parameter updates and cost history tracking

### Usage

To run the gradient descent implementation:

1. Ensure you have Python 3.x installed
2. Install required packages:
   ```bash
   pip install numpy matplotlib
   ```
3. Navigate to the gradient_descent directory and run:
   ```bash
   python grad_desc.py
   ```

### Project Structure

```
machine_learning/
├── gradient_descent/
│   ├── grad_desc.py          # Main gradient descent implementation
│   ├── lab_utils_common.py   # Common utility functions
│   ├── lab_utils_uni.py      # Univariate-specific utilities
│   └── deeplearning.mplstyle # Matplotlib style configuration
```

### Learning Objectives

This implementation helps you understand:

- The mechanics of gradient descent
- How learning rate affects convergence
- The relationship between cost function and parameter updates
- Visualization of optimization paths
- Basic linear regression concepts

### Contributing

Feel free to contribute additional machine learning implementations or improvements to existing ones. Please follow the same educational focus and clear documentation standards.

## License

This project is open source and available for educational use.
