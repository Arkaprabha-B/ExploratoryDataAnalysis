# ExploratoryDataAnalysis
## Illustration on merging of multiple datasets for implementing Machine Learning algorithms

#### 1. a. A very common scenario while working with datasets to build any model, using Machine Learning Algorithms, is the merging of different datasets of train samples. 
#### 1. b. This step arrives even before Exploratory Data Analysis. So, here is an illustration regarding the same.

#### 2.a. train1.csv: Employee Number,Employee Name,Employee Department 
are the columns in first csv file of train data

#### 2.b. train2.csv: Employee Job Level,Employee Salary
are the columns in second csv file of train data

#### 2.c. train3.csv: Employee Id ,Employee Job Level
are the columns in third csv file of train data


#### 3.a. We will have to merge these 3 train sets in order to begin with Exploratory Data Analysis.

#### 3.b. Merging will be based on Employee Number(train1.csv) and Employee Id(train3.csv); post-renaming both these columns as they are the unique identifiers.

#### 3.c. The next merge will be between the resultant of (train1.csv and train3.csv) AND train2.csv on Employee Job Level column.


#### 4. Tools and Technologies used: Jupyter Notebook, Python3, pandas (python library)
