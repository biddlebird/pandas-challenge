# Pandas Challenge README

This repository contains Python code that analyzes school district data using Pandas library. The code calculates various metrics such as average scores, passing rates, and school performance based on different criteria.

## Requirements

To run this code, ensure you have the following installed:

- Python (3.x recommended)
- pandas library (`pip install pandas`)
- tabulate library (`pip install tabulate`)

## Dataset

The analysis is performed on the following datasets:
- `schools_complete.csv`: Contains information about schools including their names, types, and budgets.
- `students_complete.csv`: Contains information about students including their scores in math and reading.

## Code Overview

### Initial Setup
- The code begins by importing necessary libraries (`pandas` and `tabulate`) and reading the CSV files (`schools_complete.csv` and `students_complete.csv`).

### Data Analysis

#### School Summary
- Calculates total number of schools, total students, total budget, and other metrics using functions such as `calculate_total_schools`, `calculate_total_students`, and `calculate_total_budget`.

#### Scores Analysis
- Calculates average math and reading scores across schools using `calculate_math_score` and `calculate_reading_score` functions.
- Determines passing rates for math, reading, and overall using functions like `calculate_math_passing`, `calculate_reading_passing`, and `calculate_both_passing`.

#### School Performance
- Analyzes school performance by sorting schools based on passing rates and displaying top and bottom performing schools.

#### Scores by School Size and Type
- Categorizes schools by size and type, and analyzes performance metrics such as average scores and passing rates for each category.

#### Scores by School Spending
- Groups schools based on spending ranges per student and analyzes performance metrics.

#### Scores by Grade
- Calculates average math and reading scores by grade level (9th, 10th, 11th, 12th) for each school.

### Output
- Uses `tabulate` to format and display the results neatly in the terminal.

## Usage
1. Clone the repository to your local machine.
2. Ensure Python and required libraries (`pandas` and `tabulate`) are installed.
3. Run the Python script to perform data analysis and view results in the terminal.

```bash
python pandas_challenge.py
