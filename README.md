# Stack Overflow Developer Survey 2023 - Data Analysis

The goal of this project is to analyze the Stack Overflow Developer Survey 2023 dataset to understand job roles, coding experience, and salary trends among developers. This analysis aims to provide insights into how different factors influence developer careers and technology adoption.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Description](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project runs with Python version 3.* and requires several libraries. To install these libraries, execute:

`pip install -r requirements.txt`

You will need to download Stack Overflow’s 2023 Developer Survey data. You can find the data to download `https://survey.stackoverflow.co/`.

Need 2 file csv are: `survey_results_public.csv` & `survey_results_schema.csv`

## Project Motivation <a name="motivation"></a>
This is an Udacity Nanodegree project. The motivation behind this project was to analyze the Stack Overflow Developer Survey 2023 data to uncover insights such as:

    - Question 1: What is the distribution of salaries among different job roles?
    - Question 2: How does the experience level (YearsCode) relate to salary?
    - Question 3: What are the most common job roles and how many developers report each role?

## File Description <a name="files"></a>
    - analysis.ipynb: Jupyter notebook containing the data analysis and visualizations.
    - analysis.html: File html export from `analysis.ipynb`.
    - survey_results_public.csv: Stack Overflow's 2023 Annual Developer Survey data.
    - survey_results_schema.csv: Schema describing the columns in the Stack Overflow 2023 Annual Developer Survey data.

## Results <a name="results"></a>
The main findings from the analysis include:

    - Most Common Job Roles: Insights into the distribution and average salaries across different developer roles.
    - Experience and Salary: How years of coding experience relate to annual salary.
    - Job Satisfaction: Variations in job satisfaction across different developer roles.

For a detailed explanation of the results and visualizations, please refer to the blog post available `https://tamokiloi.github.io/`

## Licensing, Authors, and Acknowledgements <a name="licensing"></a>
Data for this project is sourced from Stack Overflow’s 2023 Developer Survey. Credit goes to Stack Overflow for providing the data.