Problem Statements
1) Classify the features in the dataset into their appropriate data types (ordinal,
nominal, interval, or ratio). Provide a rationale for each classification.

2) Identify and describe any data quality issues or inconsistencies within the
dataset. What steps would you take to clean and preprocess the data to ensure
its accuracy and reliability for further analysis?

3) A summary statistic provides a numerical summary of a specific feature within
the dataset. There are two commonly used categories of summary statistics:
those that indicate the central tendency and those that indicate the spread of the
data. Identify the most appropriate measure of central tendency for each attribute
in the dataset and state its corresponding value. Additionally, calculate the
standard deviation and range of values for each column.

4) Using a histogram and box plot, assess the presence of outliers in the
'average_fare' and 'traffic_index' variables. Describe the visualizations and
identify what distribution do both of these variables belong to.

5) Count and identify the number of outliers in ‘average_fare’ and ‘traffic_index’
columns. Explain the method of identification and steps to resolve outliers

6) Examine the normal probability plot (Q-Q plot) for the 'rides_completed’' variable
in the dataset. Based on the shape and trend of the plot, what conclusions can
be drawn? Provide a rationale for your conclusions.

7) Calculate the correlations between all numerical variables. From this, identify
variable which has highest correlation with 'driver_availability'

8) Generare a pairplot of ‘average_fare’, ‘driver_availability’, and ‘vehicle_type” with
‘weather’ as hue in the dataset. What insights can be gained from the pair plot,
and how does it help in visualizing the relationships between these variables?

9) Use hypothesis testing to answer the following :
Define a null and alternative hypothesis to investigate whether there is no
significant difference in the average fare paid between bike and car. Use T - test
to analyze the relationship between these two variables. Plot a histogram to
analyze your hypothesis and its results. Assume significance level as 0.05.

10)Calculate the margin of error to quantify the precision of the analysis done
previously and what you can infer from the results.

11) Perform a linear regression to predict 'rides_completed' using 'average_fare',
'driver_availability', 'surge_multiplier', 'traffic_index' and 'special_event'. Plot the
predicted versus actual values of 'rides_completed'. Calculate MSE, RMSE and
R^2 values, and explain their significance.

12)In analyzing the dataset, we aim to understand factors influencing average fare
and ride completion. What additional features could be aggregated from the
existing features to enhance the predictive modeling for average fare or rides
completed (any 2 feature aggregations) ?
