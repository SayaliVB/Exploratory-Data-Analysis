# Exploratory-Data-Analysis

1. Transformation

Among the columns in the dataset, the datatype of the ‘Mileage’, ‘Engine’, ‘Power’ columns is ‘object’.Converted them to numerical columns (float or integer). This involves performing unit conversions to achieve
consistency within each column.


2. Outliers and Correlation

‘Car_Age’ feature is created and is defined as the difference between the current year and the year the car was built.
Calculated Lower Limit and Upper Limit based on IQR from scratch.
Calculated the correlation coefficient.
Printed outliers based on IQR and draw box-plots accordingly for the following columns:
‘Car_Age’, ‘Kilometers_Driven’, ‘Mileage’, ‘Engine’, ‘Power’, ‘Seats’, ‘Price’
The error data point(s) were removed/handled.
Calculated correlation coefficient and create scatterplot against ‘Price’ for the following columns:
‘Car_Age’, ‘Kilometers_Driven’, ‘Mileage’, ‘Engine’, ‘Power’, ‘Seats’.
Summarized observations with respect to data distribution, outliers, and correlation.


3. Handling missing values

There are missing values in the following columns: ‘Mileage’, ‘Engine’, ‘Power’, ‘Seats’, ‘Price’. Imputed the missing values using subclass (subgroups).


4. Outliers and Correlation with the imputed data points

Repeat #2 with the imputed data points. The resulting plots contain both original and imputed data points in different colors to distinguish one from the other.
Summarized your observations with respect to data distribution, outliers, and correlation after imputation.
