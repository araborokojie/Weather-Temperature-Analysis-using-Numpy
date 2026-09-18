# Weather-Temperature-Analysis-using-Numpy
The project focuses on understanding the difference between Python lists and NumPy arrays and applying element-wise numerical operations to real-world-style data.


## Project Overview

This project is a beginner-level numerical analysis exercise built with Python and NumPy.
The project uses temperature data collected from three weather-monitoring locations (Lagos, Abuja, and Ibadan) to demonstrate how NumPy arrays can be used to organize, compare, and perform numerical operations on data.


## Objectives

The main objectives of this project were to:

- Convert Python lists into NumPy arrays.
- Inspect NumPy arrays using attributes such as ndim, shape, dtype, and size.
- Perform element-wise arithmetic operations.
- Compare temperature readings between different locations.
- Identify the highest temperature recorded on each day.
- Simulate a 1°C increase in temperature readings.
- Understand why NumPy is useful when working with numerical datasets.


## Key Analysis

**1. Highest Temperature by Day**

The temperatures were compared across the three locations to determine which location recorded the highest temperature on each day.

- Day 1 — Lagos: 27.5°C
- Day 2 — Lagos: 29.0°C
- Day 3 — Lagos: 30.5°C
- Day 4 — Abuja: 30.0°C
- Day 5 — Abuja: 32.0°C

  
**2. Temperature Increase**

A 1°C increase was applied to every temperature value using NumPy without using a for loop.

This demonstrated NumPy's ability to perform operations across an entire array.


**3. Lagos vs Abuja Comparison**

The difference between Lagos and Abuja temperatures was calculated using:

Lagos temperature - Abuja temperature

The resulting differences were:

[2.5, 1.0, 1.0, -2.0, -1.0]

Positive values indicate that Lagos was warmer, while negative values indicate that Abuja was warmer.


## Key Learning

One of the main concepts demonstrated in this project is the difference between Python lists and NumPy arrays.

**For Python lists:**

[10, 15, 20] + [5, 10, 15]

produces:

[10, 15, 20, 5, 10, 15]

The lists are concatenated.

**With NumPy arrays:**

np.array([10, 15, 20]) + np.array([5, 10, 15])

produces:

[15, 25, 35]

The values are added element by element.

This makes NumPy particularly useful for numerical analysis because calculations and comparisons can be applied to entire arrays rather than processing each value manually.


## Findings

- Lagos recorded the highest temperature on Days 1, 2, and 3.
- Abuja recorded the highest temperatures on Days 4 and 5.
- The highest temperature in the dataset was 32.0°C, recorded in Abuja on Day 5.
- Lagos was warmer than Abuja during the first three days.
- Abuja was warmer than Lagos during the final two days.
- NumPy made it possible to perform the numerical calculations efficiently using array operations.

  
## Skills Demonstrated

- Python fundamentals
- NumPy array creation
- 1D and 2D arrays
- Array inspection
- ndim, shape, dtype, and size
- Element-wise arithmetic
- Array comparison
- np.max()
- np.argmax()
- Basic data interpretation
- Jupyter Notebook workflow


## Tools and Technologies

**Python**

**NumPy**

**Jupyter Notebook**


## Author

**Arabor Okojie**


**LinkedIn:** https://www.linkedin.com/in/arabor-okojie-9b4144376
