# MPG-Dataset-Analysis-and-Visualization
Robert Morris University - Introduction To Data Analytics 

## Analysis Summary.
#### Feature Overview: 
The generated mpg_df provides a comprehensive statistical summary of all features in the dataset, including counts, unique values, data types, and key statistical measures like mean, median, standard deviation, skewness, and kurtosis. This allows for a quick understanding of each variable's distribution and characteristics.
#### Acceleration Distribution: 
The initial histogram for 'Acceleration' reveals its distribution, which appears to be slightly positively skewed (0.29) and somewhat platykurtic (0.44), indicating a slightly flatter distribution than a normal curve. The mean acceleration is around 15.54, with a standard deviation of 2.76.

#### Impact of Cylinders on Acceleration: 
The stacked plot clearly illustrates a notable difference in 'Acceleration' between 4-cylinder and 8-cylinder vehicles. Generally, 8-cylinder cars tend to have lower acceleration times (meaning they accelerate faster) compared to 4-cylinder cars, which is evident from the shifted distributions in the histograms and the boxplot.

#### Data Range and Central Tendency: 
For example, considering 'Weight', the cars in the dataset range from 1613 to 5140 units, with a mean weight of approximately 2977.58. Similarly, 'MPG' values range from 9.0 to 46.6, with a mean of 23.45.

### Application.

#### Vehicle Design and Engineering: 
Understanding the statistical properties of features like 'MPG', 'Cylinders', 'Displacement', 'Horsepower', 'Weight', and 'Acceleration' can inform automotive engineers about design trade-offs. For example, the inverse relationship between 'Cylinders' and 'Acceleration' (meaning more cylinders often lead to better acceleration, as observed in the stacked plot) is crucial for performance optimization.
#### Consumer Guidance and Marketing: 
Car manufacturers can use this data to highlight key features and performance metrics to target specific consumer segments. For instance, knowing the typical 'MPG' and 'Weight' ranges helps in marketing vehicles for fuel efficiency or robust build. The unique count of 'Name' (301) indicates the diversity of car models available, which can be useful for market segmentation.

#### Predictive Modeling: 
The statistical summaries provide foundational insights for building predictive models. For example, understanding the skewness and kurtosis of 'Acceleration' helps in selecting appropriate statistical models or transformations for predicting vehicle performance. The variance (Std dev) of 'Weight' (849.40) suggests a wide range of vehicle sizes, which could influence predictions of other attributes.

#### Anomaly Detection: 
By knowing the typical ranges (Min, Max, 25%, 75%) and central tendencies (Mean, Median), outliers or unusual vehicle specifications can be identified. For example, a car with an 'Acceleration' far outside the observed range (8.0 to 24.8) might warrant further investigation.

#### Benchmarking and Competitive Analysis: 
The dataset allows for benchmarking against competitors. A manufacturer could compare the 'MPG', 'Horsepower', or 'Acceleration' of their vehicles against the overall distribution in the market to identify areas for improvement or competitive advantages.
