# Mean-Variance-Standard Deviation Calculator

This is my first project for the **freeCodeCamp Data Analysis with Python Certification**. It demonstrates the use of the **NumPy** library to process data and perform statistical analysis on a 3x3 matrix.

## Project Goal
The goal of this project is to create a function that takes a list of 9 digits and converts them into a 3 x 3 Numpy array. The function then calculates the mean, variance, standard deviation, max, min, and sum for:
* Each column (Axis 0)
* Each row (Axis 1)
* The flattened matrix

## Tools Used
* **Python 3**
* **NumPy**: Used for efficient numerical computations and matrix manipulation.
* **Google Colab**: Used as the primary development environment.

## Skills Demonstrated
* Data cleaning and validation (handling list length errors).
* Matrix reshaping and axis-based calculations.
* Formatting complex numerical data into structured Python dictionaries.

## How to Run
To see the results, run the `main.py` file or call the `calculate()` function with a list of 9 integers:
```python
import mean_var_std
print(mean_var_std.calculate([0,1,2,3,4,5,6,7,8]))

Created by Robert M. Kastanya as part of the Data Analysis learning path.
