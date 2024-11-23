# Customer-Churn
Bank Customer Churn: Insights &amp; EDA for modelling

# About this project:
This project is about understanding and predecting the customer churn for a bank by analysing and preparing customer data for modelling. I have read in data using python pandas module followed the several steps like understanding the data and cleaning the data and EDA and featuring enginnering.

For understanding the data i have used pandas modules to read in data types and deep dive into the finding the missing values and any wrong data types . After analysing the data, replaced the missing the values to the appropriate values and corrected the data types. for identifying the missing and duplicated values i have used .isna() and duplicated() method and corrected the data.

After then i have merged the data from the two sheets excel files into a single data frame and performed exploratory data analysis using Box lots and barplots and identified several insights regarding the customer who exited Vs non-exited. Here we have identified extreme outliers. We have not removed the outliers instead we will use this in data modelling if any skew is observed then we can apply log transformation later.

Then conducted feature engineering and created a salary vs balance ratio column which might act as significant feature for data modelling. After prepping the data for modelling removed all the text field columns and ensured the data is in single table and non null with correct data types. By understanding the characteristics of customers likely to leave, the bank can make informed decisions to improve customer satisfaction and retention.
