# COSC 442 - Assignment 1: Portfolio Optimization with Hill Climbing and Genetic Algorithms

## Authors:

- Amna Bubshait (A00723)
- Zahra Alshehabi (A00755)

## Problem:

This assignment explores portfolio optimization using Hill Climbing and Genetic Algorithms. The goal is to find the best combination of investments (from the S&P 500) to maximize returns or minimize risk. We compare the performance of both algorithms based on solution quality, convergence rate, time complexity, and sensitivity to parameters.

## Dataset:

The primary dataset used is the "S&P 500 Stocks" dataset from Kaggle:

[Dataset URL](https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks/data)

## Methodology:

1. **Load and Explore the Dataset:** Import necessary libraries, load the dataset, and perform initial data exploration.
2. **Identify and Handle Missing Values:** Identify and handle missing values using imputation techniques.
3. **Standardize Data:** Standardize numerical features to ensure fair comparison between algorithms.
4. **Portfolio Optimization:** Implement Hill Climbing and Genetic Algorithms to optimize portfolio selection based on a fitness function (Sharpe ratio approximation).
5. **Performance Metrics:** Evaluate and compare the performance of both algorithms using metrics such as solution quality, convergence rate, time complexity, and space complexity.
6. **Comparison and Results:** Analyze the results and draw conclusions about the effectiveness of each algorithm for portfolio optimization.

## Results:

- The Hill Climbing algorithm generally outperforms the Genetic Algorithm in terms of solution quality.
- Hill Climbing takes slightly longer to converge but uses less memory.
- Sensitivity analysis shows that the Genetic Algorithm's performance can be improved by adjusting parameters like mutation rate and population size.

## Conclusion:

For this specific portfolio optimization problem, Hill Climbing appears to be the more effective algorithm.

## Running the Notebook:

1. Make sure you have the necessary libraries installed (`kagglehub`, `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`).
2. Download the dataset from the provided Kaggle link.
3. Open and run the notebook in Google Colab.
