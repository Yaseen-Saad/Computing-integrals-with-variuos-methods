# Numerical Integration Comparison

## Overview

This project compares three numerical methods for computing the integral:

I = ∫[0 to 1] e^(-x^2) dx

The methods implemented are:
- **Trapezoidal Rule**: Uses trapezoids to approximate the integral by dividing the interval into n equal parts.
- **Simpson’s Rule**: Uses quadratic polynomials for higher accuracy (requires n to be even).
- **Monte Carlo Method**: Uses randomly sampled points to estimate the integral by averaging the function values.

The accuracy of each method is compared to the exact integral value using SciPy.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- SciPy

Install the required packages:
```
pip install numpy matplotlib scipy
```
## Usage
1. Clone the repsoitory:
```
git clone <repo-url>
cd <repo-name>
```
2. Run the script to compute the integral and dislpay the comparison plot
```
python Computing_integrals.py
```
## Methods
1. **Trapezoidal Rule**: Approximates the area under the curve by dividing it into trapezoids.
2. **Simpson's Rule**: Uses quadratic polynomial approximations for improved accuracy. Requires n to be even.
3. **Monte Carlo Method**: Generates random points within the interval to estimate the average value of the function.

Each method is implemented for n = 10, n = 100, and n = 1000.

## Output

The script generates a plot comparing the results of the Trapezoidal Rule, Simpson's Rule, and Monte Carlo Method with the exact result (calculated using SciPy).

### Example Plot

The plot will display the computed integrals for each method and the exact integral value as a reference. It uses a logarithmic scale on the x-axis to represent different values of n.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.