# Exploratory Data Analysis
{: .hidden-title }

## Overview

Exploratory Data Analysis (EDA) is the process of examining and understanding data before you start modeling or drawing conclusions. Think of it as getting to know your data — its structure, patterns, outliers, and relationships — before jumping into statistical modeling or machine learning.

The main goals of EDA are to:
- Understand the shape and structure of your data (e.g., data types, missing values, distributions)
- Detect patterns or trends (e.g., Does fuel usage increase with distance?)
- Identify outliers or anomalies (e.g., One trip used way more fuel than expected)
- Test initial hypotheses about relationships between variables
- Inform further analysis or model building

Common EDA techniques:
- Descriptive statistics: Mean, median, standard deviation, etc.
- Data visualization: Histograms, scatter plots, box plots, correlation heatmaps
- Handling missing data and checking data types
- Grouping and summarizing data (e.g., average fuel use per car model)

Example (fuel and driving data):
If you had a dataset of car trips, EDA might involve:
- Plotting distance vs. fuel used to spot trends
- Checking if longer trips are more fuel-efficient
- Finding and understanding any unusual trips
- Looking at fuel use by car type, driver, or route

## Activities

### Tutorial
The main tutorial activity for this unit aims to explain the importance and purpose of EDA in data science and machine learning projects. It emphasizes that skipping EDA leads to poor outcomes, while doing it well ensures that your data is valid, meaningful, and ready for machine learning. It also outlines some key methods and concepts used in EDA, such as visualizations, summary statistics, and data profiling.

While the notebook contains many issues due to funtionality deprication in the libraries it uses, once these were fixed it is an excellent resource covering a lot of ground on the EDA process. Here's a liink to the notebook on colab.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit02/Unit02%20A%20Tutorial%20on%20Exploratory%20Data%20Analysis.ipynb)

### Auto MPG

This activity required some basic EDA to be performed on the supplied dataset, the main deliverables were:

- Identify missing values
- Estimate Skewness and Kurtosis
- Correlation Heat Map
- Scatter plot for different parameters
- Replace categorical values with numerical values (i.e., America 1, Europe 2 etc.)

Here's a link to the completed notebook on colab.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit02/auto_mpgh.ipynb)

## Reflection

This week’s focus on Exploratory Data Analysis (EDA) really emphasized how important it is to understand your data before diving into any modeling. It felt a bit like investigative work—looking for patterns, identifying outliers, and getting a clear sense of the dataset’s structure. The tutorial covered key techniques like visualizations, summary statistics, and managing missing data, all of which helped build a stronger understanding of the data. Although the notebook initially had some issues due to deprecated libraries, once those were resolved, it proved to be a very valuable resource. It was also especially useful in our team project, where applying EDA principles gave us a solid foundation for deeper analysis.


[Back to Machine Learning](/machine_learning/)