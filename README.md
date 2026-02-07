# Exam Prediction Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [References](#references)


### Project Overview
This is a dataset that consist of 13 columns and 20000 rows. The are 2 columns that consist of integers, 3 are floats while the rest are object. It is a CSV file.
#### Column descriptions:
- internet access: This means those learners that has or does not have access to the internet
- Course: It shows the academic degrees that are awarded


### Data Source
The dataset is gotten from XYZ school

### Tools used
The tools use fo this project includes
- Excel(pivot tble used to aggregate the data)
- Python(pandas) used for data manipulation

### Data Cleaning/Preparation
- Missing values were filled before visualization
- The column header(course) was renamed to degree for easy comprehension
- The date column was splitted into Year, Month and Day

### EDA 
1. What is the total number of learners that have access to the internet?
2. Which of the gender has the highest exam score?
3. What is the average score of those with internet access?

### Results/Findlinds
```
SELECT COUNT(*) FROM
EXAM SCORE
WHERE internet_access = "Yes"
```
### Recommendations
1. The school should ensure that all learners have equal opportunity to internet access
2. Pairing of both gender during studying.

# References


