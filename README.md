# Wallmart-Sales
### Sales and weather prediction

# Data

You have been provided with sales data (sales.csv) for 111 products whose sales may be affected by the weather (such as milk, bread, umbrellas, etc.). These 111 products are sold in stores at 45 different Walmart locations. Some of the products may be a similar item (such as milk) but have a different id in different stores/regions/suppliers.
The 45 locations are covered by 20 weather stations (i.e., some of the stores are nearby and share a weather station). The key data (key.csv) indicates for each store to which weather station it belongs.
In addition, you have been provided with the weather data (weather.csv) of each weather station.
The data can be found here.
The sales and weather data are daily observations, from January 2012 to October 2014.
You should use the observations from the years 2012-2013 as your training data, and the observations from the year 2014 as your test data.

Section A (Data Exploration and Visualization)

Explore the data using tables, visualizations, and other relevant methods.
• Plots should have an informative main title, axis labels and a legend.
• For each plot or table, provide a short description of key observations. Make sure to only include content which would be meaningful for a Walmart store district manager.
• The goal of this section is to get insights on the data which may or may not be relevant for the following sections.


Section B (Data Pre-processing)

Apply different methods of pre-processing to the data in order to prepare it
for the models you wish to apply in the next sections.
• Apply at least one type of imputation, one of transformations, and one
of exclusion (i.e., feature selection).
• Provide an explanation to each method you apply. Your choice should
reflect an understanding of the method and why it’s needed.

Section C (Unit Sales Prediction)

Sum up the unit sales of product 5, 6, 9, 16, 45 to a new value called key_sum.
Use at least two different machine learning models to predict the daily sales
figures of key_sum per store on a given day using the weather and sales data.
• You can use all the data except for the features used to create key_sum
(this rule only applies for this section).
• Feel free to create additional features based on analysis that you have
produced.
• The implementation should include parameter tuning.
• Report a suitable measure to evaluate the performance of each model
and compare the results.
• Present the models’ results in a plot.

Section D (Rainy Day Prediction)

Based solely on the sales data table, use two different machine learning
models to predict if on a given day it rained or not for store number 11.
• A rainy day is defined as a day in which the precipitation (preciptotal
column), is greater than 0. Trace (T) is defined to be greater than 0.
• The implementation should include parameter tuning.
• Report a suitable measure to evaluate the performance of each model
and compare the results.


Section E (Elevation Estimation)

Estimate the elevation of each weather station based on the weather data.
• Note that there is no elevation data for the weather stations so you must come up with a way to estimate it using the given data (This is not a guess, there is a way to measure this using the given data).

Section F (Clustering)

Apply a clustering algorithm on the weather data to cluster the weather stations. Can you identify similarities inside the clusters or differences between them? Discuss your findings and find a way to demonstrate visually what similarities the clusters may have.

Section G (Performance)

Machine learning models that outperformed other students’ models for either the unit sales predictions or the rainy-day classification may get additional points as long as the non-standard methodology to obtain superior results is also explained.
• In order to get the bonus points you may want to apply multiple performance measures to ensure that we can compare your performance on an equal basis to other projects, and that you did not sacrifice performance in a specific measure to outperform in another.
