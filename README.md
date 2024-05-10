# Machine Learning Project Readme

## Outlier Detection and Removal

In this project, we aim to detect and remove outliers from the dataset using various methods:

1. **Mean Function:** Outliers will be identified by comparing data points with the mean of the dataset.

2. **Percentile Method:** Outliers will be detected based on their position relative to the data distribution using percentiles.

3. **Interquartile Range (IQR) Method:** Outliers will be identified using the IQR, which is the range between the first and third quartiles of the data.

4. **Normal Distribution:** Outliers will be detected based on their deviation from the normal distribution assumption.

5. **Z-score Method:** Outliers will be identified by calculating the z-score of each data point and comparing it to a threshold.

Dataset used for outlier detection: [Link to Dataset](https://drive.google.com/file/d/1UlWRYU0UglE2ex3iFse0J6eCLEU8g98P/view?usp=sharing)

## Hypothesis Testing

### Q1: Child Psychologist's Claim

A child psychologist claims that the average time working mothers spend talking to their children is at least 11 minutes per day. We conduct a random sample of 1000 working mothers and find they spend an average of 11.5 minutes per day talking with their children. 

- Population Standard Deviation: 2.3 minutes
- Sample Size: 1000
- Sample Mean: 11.5 minutes
- Significance Level: α = 0.05

We perform a hypothesis test to determine if there is enough evidence to support the psychologist's claim.

### Q2: Coffee Shop's Claim

A coffee shop claims that their average wait time for customers is less than 5 minutes. To test this claim, a sample of 40 customers is taken, and their wait times are recorded. 

- Sample Size: 40
- Sample Mean Wait Time: 4.6 minutes
- Sample Standard Deviation: 0.8 minutes
- Significance Level: α = 0.05

We perform a hypothesis test to determine if there is enough evidence to support the coffee shop's claim.

### Instructions for Running the Code

1. Download the dataset from the provided link.
2. Execute the code for outlier detection and removal using different methods.
3. Perform hypothesis testing for both questions using the provided data and parameters.
4. Analyze the results and determine the conclusions based on the hypothesis tests.

## Data Preprocessing

### Overview

The Data Preprocessing Toolkit is designed to streamline the process of preparing datasets for machine learning applications. By addressing common data quality issues such as missing values, outliers, and inconsistent formatting, this toolkit aims to enhance the integrity and usability of datasets.

Dataset : [Link to Dataset]([https://drive.google.com/file/d/1UlWRYU0UglE2ex3iFse0J6eCLEU8g98P/view?usp=sharing](https://drive.google.com/file/d/1F3lRf32JM8ejnXq-Cbf9y7fa57zSHGz_/view?usp=sharing))

### Features

- **Data Exploration:** Understand the structure of the dataset, identify unique values, and perform basic statistical analysis.
- **Data Cleaning:** Handle missing values, remove duplicates, and address outliers to ensure data reliability.
- **Data Analysis:** Filter and visualize data based on specific criteria to gain insights and inform decision-making.
- **Data Encoding:** Convert categorical variables into numerical representations to facilitate machine learning algorithms.
- **Feature Scaling:** Standardize or normalize feature values to improve model performance and convergence.

### Usage

- **Exploration:** Use the provided functions to explore the dataset, identify potential issues, and gain insights into the data structure.
- **Cleaning:** Utilize the data cleaning functions to handle missing values, remove duplicates, and address outliers according to the project requirements.
- **Analysis:** Filter and visualize the data using the analysis functions to extract meaningful information and support decision-making processes.
- **Encoding:** Apply data encoding techniques to convert categorical variables into numerical representations suitable for machine learning algorithms.
- **Scaling:** Standardize or normalize feature values using feature scaling functions to ensure consistent data ranges and improve model convergence.

### Next Steps

- **Experimentation:** Explore different preprocessing techniques and evaluate their impact on data quality and model performance.
- **Feedback:** Share feedback on the toolkit usability, suggest improvements, or contribute additional features to enhance the preprocessing system.
- **Documentation:** Maintain comprehensive documentation to guide users on how to utilize the toolkit effectively and troubleshoot common issues.
