# Daily-data-usages-analysis-on-monthly-basis
Project Overview and Objectives
This project focuses on analyzing simulated daily usage data (e.g., WiFi usage, internet activity) for each month of the year. The primary objectives are to:

Understand Daily Usage Patterns: Visualize the fluctuation of daily usage over the course of each month.
Calculate Key Descriptive Statistics: Summarize the usage data to understand its central tendency and spread.
Identify Anomalous Usage Days (Peak Days): Implement two common statistical methods — Z-score and Standard Deviation — to detect days with unusually high or low usage, which can be considered ‘peak days’ or ‘outliers’.
Basic Theory and Prerequisites
To perform this analysis, we utilize fundamental statistical concepts and Python libraries:

NumPy: A powerful library for numerical operations in Python, essential for handling array data and statistical calculations.
Matplotlib: A comprehensive library for creating static, animated, and interactive visualizations in Python.
Key Statistical Concepts:

Line Plots : Visual representation that show how a variable changes over a continuous range , perfect for time-series data like daily usage.
Mean : The average of value of a dataset
standard Deviation : A measure of the amount of variation from the mean value
Z-score: Also known as a std score , the z-score indicates how many std deviations an element is from the mean.
Z-score outlier : This method identifies outlier as data points that fall outside a certain number of std deviation
Step- by- Step Implementation

Data Generation : First , we take the dictionary of months variable to store the no. of days in each months. Then we generate the data usages for each months in the range(1,10). According the no. of days in each months data usages will be generated in list of each months like this January_data: [7 5 4 6 5 4 3 1 1 6 3 8 8 3 4 5 9 7 6 8 1 9 4 9 9 8 1 4 5 3 5]
2. Descriptive Statistics : We have to calculate the maximum, minimum, mean, median , and standard deviation for each month’s usages data.
e.g for January, we see a maximum usage of 9, a minimum of 1, an average (mean) of approximately 5.19, a median of 5.0, and a standard deviation of about 2.51. These values help characterize the usage patterns for each month.

3. Visualizing Daily Usage:

Line Plots: Plot the line of usages data on y-axis and no. of days on x-axis for each months
Z-score Outlier: Plot the z-score outlier which help to find the unusual data usages in the graph of each months . In my project i have taken the value of threshold is 2 , so it will show as an outlier when deviation of data usages from the -2 to +2 .
Std. deviation : The graph of std. deviation tell a/t the deviation of data usages from the mean value of each months .
Conclusion
This project demonstrated a straightforward yet effective approach to analyzing daily usage patterns and identifying anomalies. By simulating usage data and employing descriptive statistics, line plots, Z-score, and standard deviation methods, we can gain valuable insights into daily fluctuations and pinpoint ‘peak days’ that deviate significantly from the norm.

These techniques are highly applicable in various real-world scenarios, such as monitoring network traffic, website visits, energy consumption, or any time-series data where identifying unusual activity is crucial for performance optimization, security, or resource management. The ability to visualize these patterns and statistically flag outliers provides a powerful tool for proactive decision-making.
