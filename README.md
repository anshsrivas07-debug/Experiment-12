Experiment No. 12: Data Preprocessing and Handling Missing Values using Python
Name: Vibhas Shukla PRN: 25070123164 Branch: F.Y. E&TC (2025–29) Batch: A1 Subject: Exploratory Data Analysis with Python

1. Aim
The aim of this experiment is to study and perform data preprocessing techniques and learn how to handle missing values in datasets using Python, in order to improve data quality and make it suitable for analysis.

2. Objective
To understand the importance of data preprocessing in data analysis. To identify and handle missing values in datasets. To learn techniques such as removing, replacing, and imputing missing data. To perform data cleaning operations like type conversion and formatting. To prepare clean and structured datasets for further analysis.

3. Concepts Used
3.1 Data Preprocessing
Data preprocessing is the process of cleaning and transforming raw data into a usable format. It is an essential step before performing any analysis.

3.2 Missing Values
Missing values are the data points that are not present or are undefined in the dataset. They are often represented as null or empty values.

3.3 Detection of Missing Values
Missing values can be identified using logical checks that indicate whether a value is present or not.

3.4 Handling Missing Values
There are several techniques to handle missing values:

Removing missing data
Replacing missing values with constants Filling missing values using statistical methods

3.5 Data Type Conversion
Changing data from one type to another (e.g., string to numeric) to make it suitable for calculations.

3.6 Data Cleaning
Cleaning involves removing inconsistencies, correcting formats, and standardizing data.

4. Theory
4.1 Introduction to Data Preprocessing
In real-world scenarios, datasets are often incomplete, inconsistent, and contain errors. Such data cannot be directly used for analysis. Therefore, preprocessing is required to clean and organize the data. Handling missing values is one of the most critical steps in preprocessing.

4.2 Missing Values and Their Impact
Missing values can occur due to:

Data entry errors System failures Incomplete data collection Impact of Missing Values: Reduces accuracy of analysis Leads to incorrect conclusions Affects performance of machine learning models

4.3 Methods to Handle Missing Values
Removing Missing Values
Rows or columns containing missing values can be removed. Useful when the missing data is very small. 2. Replacing Missing Values with Constants

Missing values can be replaced with fixed values such as zero or a placeholder. 3. Statistical Imputation

Missing values can be replaced using statistical measures: Mean (average value) Median (middle value) Mode (most frequent value)

4.4 Data Cleaning and Transformation
Replacing Invalid Data Sometimes missing values are represented using symbols like "_" or text. These must be converted into proper missing values.

Data Type Conversion Columns may contain mixed data types. Converting them into numeric form ensures proper calculations.

Handling Inconsistent Formats Text data may have inconsistent formatting (uppercase/lowercase). Standardization improves data consistency.

Date Format Issues Dates may appear in different formats and need to be standardized.

4.5 Dataset Cleaning Process
The dataset undergoes several preprocessing steps:

Identification of missing values Replacement of invalid symbols with proper missing values Conversion of data into appropriate numeric types Filling missing values using mean, median, or mode Standardizing text formats Saving cleaned data into a new dataset

4.6 Dataset Analysis
After cleaning, the dataset is analyzed using the following:

Size of Dataset
Total number of elements present in the dataset. 2. Shape of Dataset

Represents the number of rows and columns. 3. Dataset Information

Provides details about data types and non-null values. 4. Viewing Data

First few and last few rows are checked to understand the structure. 5. Handling Missing Values in Real Dataset

Missing values in numerical columns are replaced using mean. Missing categorical values are replaced using mode.

4.7 Importance of Data Preprocessing
Improves data quality and reliability Ensures accurate analysis and results Makes data suitable for machine learning models Reduces errors and inconsistencies Helps in better decision-making

5. Conclusion
In this experiment, data preprocessing techniques and methods to handle missing values were successfully studied and applied. Various strategies such as removing missing data, replacing it with constants, and using statistical methods like mean, median, and mode were used to clean the dataset.

The experiment also demonstrated the importance of converting data types, correcting inconsistencies, and standardizing formats. After preprocessing, the dataset became clean, structured, and ready for analysis.

Overall, this experiment highlighted the critical role of data preprocessing in exploratory data analysis and showed how Python provides powerful tools to efficiently clean and prepare data for further use.
