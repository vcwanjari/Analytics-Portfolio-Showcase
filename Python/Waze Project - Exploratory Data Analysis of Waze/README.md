# Waze Project - Exploratory Data Analysis of Waze

## Project Overview

The Waze Project focuses on conducting exploratory data analysis (EDA) on real-world traffic data sourced from the Waze navigation app. The objective of this project is to uncover insights about traffic patterns, congestion hotspots, and factors affecting commute times. By analyzing the available data, we aim to provide valuable information that can help transportation authorities and urban planners make informed decisions to optimize traffic flow and enhance the overall commuting experience.

## Dataset

The dataset used for this project consists of anonymized and aggregated traffic data collected from the Waze navigation app. It includes information such as traffic incidents, road closures, congestion levels, and travel times. This dataset provides a rich source of information about real-time traffic conditions, enabling us to gain insights into factors influencing traffic patterns and identify areas for improvement.

## Approach

1. **Data Cleaning and Preparation**: The initial step involved cleaning and preprocessing the dataset. We handled missing values, removed duplicates, and standardized the data format for consistency. Additionally, we performed data validation checks to ensure data integrity and accuracy.

2. **Exploratory Data Analysis**: In this phase, we conducted exploratory data analysis to uncover insights about traffic patterns and congestion. We examined factors such as peak traffic hours, recurring congestion hotspots, and the relationship between traffic incidents and commute times. Through the use of descriptive statistics, visualizations, and data aggregation techniques, we aimed to identify trends, outliers, and potential areas for improvement.

3. **Data Visualization**: To effectively communicate our findings, we utilized various data visualization techniques such as maps, charts, and graphs. These visualizations helped in highlighting traffic patterns, congestion hotspots, and other relevant insights. By visualizing the data, we made it easier for stakeholders to understand the findings and make data-driven decisions.

4. **Key Findings and Insights**: Based on the exploratory data analysis, we derived key findings and insights that provide a deeper understanding of traffic patterns and congestion dynamics in the studied area. These findings may include identifying recurring traffic bottlenecks, peak congestion hours, and potential factors contributing to congestion. Additionally, we may uncover insights that can guide urban planning decisions, infrastructure improvements, and traffic management strategies.

## Key Findings

- Nearly all the variables were either very right-skewed or uniformly distributed. For the right-skewed distributions, this means that most users had values in the lower end of the range for that variable. For the uniform distributions, this means that users were generally equally likely to have values anywhere within the range for that variable.
- Most of the data was not problematic, and there was no indication that any single variable was completely wrong. However, several variables had highly improbable or perhaps even impossible outlying values, such as `driven_km_drives`. Some of the monthly variables also might be problematic, such as `activity_days` and `driving_days`, because one has a max value of 31 while the other has a max value of 30, indicating that data collection might not have occurred in the same month for both of these variables.
- Less than 18% of users churned, and \~82% were retained.
- Distance driven per driving day had a positive correlation with user churn. The farther a user drove on each driving day, the more likely they were to churn. On the other hand, number of driving days had a negative correlation with churn. Users who drove more days of the last month were less likely to churn.

## Conclusion

The "Waze Project - Exploratory Data Analysis" provides valuable insights into traffic patterns and congestion dynamics in the studied area. By conducting exploratory data analysis on the Waze dataset, we have gained a deeper understanding of factors affecting traffic flow and identified potential areas for improvement. The findings from this project can guide transportation authorities, urban planners, and decision-makers in optimizing traffic management strategies, implementing infrastructure improvements, and enhancing the overall commuting experience.


