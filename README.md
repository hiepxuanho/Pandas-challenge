# Pandas-challenge
# School District Performance Analysis

## Overview
As the newly appointed Chief Data Scientist for our city's school district, my primary responsibility is to assist the school board and the mayor in making strategic decisions regarding future school budgets and priorities. This project involves the analysis of district-wide standardized test results to uncover key trends and insights about school performance.

## Objective
The objective of this project is to aggregate and analyze student performance data across all schools in the district. By exploring various metrics such as math and reading scores and school-specific information, we aim to identify trends in school performance that can help guide decision-making for the district.


## Tasks
1. **Data Aggregation**: Combine student performance data with school-specific information.
2. **Trend Identification**: Analyze key metrics to uncover trends in school performance, including:
   - Overall district-wide performance.
   - Comparison between schools.
   - Performance based on school size, type, and funding.
3. **Insights Generation**: Provide insights and recommendations based on the aggregated data.

## Analysis Approach
- **Exploratory Data Analysis (EDA)**: Understand the structure and key characteristics of the dataset.
- **Data Visualization**: Use visual tools to illustrate trends and compare school performance metrics.
- **Statistical Analysis**: Apply relevant statistical methods to highlight significant trends in performance.
  
## Tools and Technologies
- **Python**: For data manipulation, analysis, and visualization.
- **Pandas**: For efficient data handling and aggregation.
- **Matplotlib**: For creating meaningful visualizations of the data.
- **Jupyter Notebook**: For an interactive analysis environment.

## Expected Outcomes
By the end of this project, we aim to deliver:
- A descriptive report showcasing district-wide trends in standardized test scores.
- A comparison of performance across schools with potential insights into the factors driving these trends.
- Strategic recommendations to assist in decision-making regarding school budgets and priorities.

## How to Use This Repository
1. Clone the repository:
    ```bash
    git clone https://github.com/hiepxuanho/Pandas-challenge
    
    ```
2. Install/Imported the required dependencies:
    ```bash
    pip install --upgrade ipython
    pip install --upgrade notebook

    import matplotlib.pyplot as plt
    import pandas as pd
    ```
3. Open and run the Jupyter notebooks to explore the analysis and visualizations.
    ```bash
    conda activate dev
    jupyter notebook
    ```

## Note:
The first half of the project was pretty straight forward involves using functions such as mean(), count(), unique() 
I got stuck at the part where we needed to calculate the total school budget and per capita spending per school from school_data. The professor had to explain the logic and showed me the sample code of how to find it.
/-----------------------------------/
per_school_budget = school_data.set_index(["school_name"])["budget"]
per_school_capita = per_school_budget / per_school_counts
/-----------------------------------/

