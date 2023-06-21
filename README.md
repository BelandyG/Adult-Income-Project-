# **Adult income dataset**
An individual’s annual income results from various factors. Intuitively, it is influenced by the individual’s education level, age, gender, occupation, and etc. The goal is to predict if an individual's annual income excceds $50,000 based on census data.

**Author**: Belandy Gard

Source of data:

https://www.kaggle.com/datasets/wenruliu/adult-income-dataset?resource=download

# **Data Dictionary**
![image](https://github.com/BelandyG/Adult-Income-Project-/assets/123032319/a5bc4451-3320-41a3-ae66-abb0172c0361)


# **Cleaning**
Before machine learning preprocessing, the data was cleaned with the following steps:

- Rows and columns were calculated
- THe data tpe of each variable was checked
- Duplicate rows were dropped
- Spelling inconsistencies were fixed
- Categorical ordinal data was numerically encoded

 # **Exploratory Visualization**
To understand the data statistical analyses Exploratory Visualization was completed to explain, or model the data. This was done by each of thed following:

- Histogram to view the distributions of various features in your dataset.
- Boxplot to view statistical summaries of various features in your dataset.
- Heatmap of the correlation between features.


The following heatmap shows the corealation coefficient between each numeric variable. This is another was to visualize the information provided above.

![image](https://github.com/BelandyG/Adult-Income-Project-/assets/123032319/dd8e88d8-68c8-4b3e-b47a-aedd3da122ce)


Analyzed Histograms for all categorical columns on income greater, less than and equal to $50K.

![image](https://github.com/BelandyG/Adult-Income-Project-/assets/123032319/bc8b37cf-3806-4b43-8d76-de90770e3bd0)

![image](https://github.com/BelandyG/Adult-Income-Project-/assets/123032319/245ba8ea-ddec-42dd-ac48-21f660b91bc3)


# **Two visualizations for Stakeholder**

From the following analysis we can determine individuals making more than 50K, the average age of that group is 44. Where those making less than 50K, the average age is 36.

![image](https://github.com/BelandyG/Adult-Income-Project-/assets/123032319/b9e27fd9-2af2-4b3b-818b-5d203b77f096)

 Looking at this visual we can determine there are more females making more than $50K

![image](https://github.com/BelandyG/Adult-Income-Project-/assets/123032319/e4ccf5e9-af91-47b9-abc5-47ffc1cdd3c7)


# **Machine Learning**

The data was preprocessed before fitting and testing machine learning models with the following steps:

Missing numerical values were imputed with the mean
Numerical features were scaled
Missing nominal values were imputed with the most frequent value
Nominal features were one-hot encoded


# **Random Forest**

![image](https://github.com/BelandyG/Adult-Income-Project-/assets/123032319/82d22b85-7c1c-41bc-8b2f-dc499ff91414)


# **Decision Tree Model**

![image](https://github.com/BelandyG/Adult-Income-Project-/assets/123032319/855a957a-3fde-4fdf-8da6-abaf7a63cd55)


# **Linear Regression Model**

![image](https://github.com/BelandyG/Adult-Income-Project-/assets/123032319/6844a154-f8fb-414d-a42e-766cb505c9d1)


# **Final Recommendations**

Based on my evaluation of the metrics for each model, The Logistics egression model shows the best results for my business problem. The goal is to determine the best precision for income greater, less than or equal to $50k. This model provides the best testing score.
