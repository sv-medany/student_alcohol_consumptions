# Student Alcohol Consumption Data Analysis

In this project, we'll analyze a dataset containing information about student alcohol consumption. The analysis involves various operations using the Pandas library to manipulate and explore the data.

## Project Overview

This repository contains Python code for analyzing student alcohol consumption data using the Pandas library. The analysis includes steps to import the dataset, manipulate strings, capitalize specific columns, and perform mathematical operations on the dataset. The primary objectives of this project are:

- Import the student alcohol consumption dataset.
- Capitalize specific columns in the dataset.
- Print the last elements of the dataset.
- Create a function to identify legal drinkers.
- Multiply every numerical value in the dataset by 10.

## Analysis Steps

1. Import the necessary libraries, including Pandas and NumPy.
2. Import the student alcohol consumption dataset using a provided URL.
3. Assign the dataset to a variable named `df`.
4. Slice the DataFrame to include columns from 'school' to 'guardian'.
5. Define a lambda function to capitalize strings.
6. Capitalize the 'Mjob' and 'Fjob' columns using the lambda function.
7. Print the last elements of the dataset using the `tail()` method.
8. Create a function called `majority` to identify legal drinkers.
9. Add a new column 'legal_drinker' using the `majority` function.
10. Define a function `mult` to multiply numerical values by 10.
11. Use the `applymap()` method to apply the `mult` function to the entire dataset.

## Repository Structure

```
Student-Alcohol-Consumption-Analysis/
│
├── alcohol_consumption_analysis.ipynb  # Jupyter Notebook containing analysis code
└── readme.md                            # Project overview and details
```

## Usage

1. Clone the repository: `git clone https://github.com/your-username/Student-Alcohol-Consumption-Analysis.git`
2. Navigate to the repository: `cd Student-Alcohol-Consumption-Analysis`
3. Open the `alcohol_consumption_analysis.ipynb` notebook to access the detailed analysis steps and results.

## Acknowledgments

- Special thanks to the source that provided the student alcohol consumption dataset for analysis.
- Appreciation to the creators and contributors of the Pandas and NumPy libraries for enabling data analysis.

---
