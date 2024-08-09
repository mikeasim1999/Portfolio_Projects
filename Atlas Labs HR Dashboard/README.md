# Data Transformations
This project started with three CSV's: a Employee Dataset, Education Field dataset, and a Survey dataset

To begin the data transformation process, I started with the Survey dataset. The original structure had each category as their own seperate columns rather than in one column. There were two types of surveys in this dataset, surveys about how employees feel about their job and enviorment and a performance survey done by the employees and their managers. In order to properly analyze the survey data, I decided that it would be best to unpivot the category and answer columns creating a category column for job and enviorment ratings, an answer column for job and enviorment ratings, a category column for performance ratings, and a column for performance rating answers.

##Before Transformation
![Survey Data Before Transformation](https://github.com/user-attachments/assets/bc0680e4-5ee4-49ea-88fe-904a5f4cf78e)

##After Transformation
![Survey Data After Transformations](https://github.com/user-attachments/assets/4caaa050-5266-4e59-aa8b-dc35610ce049)

