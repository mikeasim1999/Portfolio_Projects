# Data Transformations
This project started with three CSV's: a Employee Dataset, Education Field dataset, and a Survey dataset

To begin the data transformation process, I started with the Survey dataset. The original structure had each category as their own seperate columns rather than in one column. There were two types of surveys in this dataset, surveys about how employees feel about their job and enviorment and a performance survey done by the employees and their managers. In order to properly analyze the survey data, I decided that it would be best to unpivot the category and answer columns creating a category column for job and enviorment ratings, creating a category and answer column for both types of surveys. After the unpivot transofrmation were complette, I added two conditional columns and would rank each answer. This is so that I could sort the answer columns.
## Before Survey Transformation
![Survey Data Before Transformation](https://github.com/user-attachments/assets/bc0680e4-5ee4-49ea-88fe-904a5f4cf78e)

## After Survey Transformation
![Survey Data After Transformation](https://github.com/user-attachments/assets/757e8201-7148-4e95-839a-2081d50ede34)

The last transformation i performed was creating a bridge table between the employee and survey tables. 

# Data Model

![Data Model](https://github.com/user-attachments/assets/2664daf6-3747-4471-b011-f4971efabfba)

# Report

## Landing Page
![AL Landing Page](https://github.com/user-attachments/assets/4ae24bd6-eb45-49fe-b161-350109d39ea7)

## Employee Overview
This is a simple breakdown of the employees who do/have worked for Atlas Labs
![Employee Overview](https://github.com/user-attachments/assets/dac6c03f-bc03-4328-817d-ce70c16737b1)

## Survey Analysis
Now we can see the reason why I performed the transformation I did on the Survey table. The top two visuals show the category on the y-axis and have the answers sorted from worst to best. This is possible becuase of the transformations performed.
![Survey Analysis](https://github.com/user-attachments/assets/b417f01a-f7e0-4b5d-a188-1122dc33be0d)

## Attrition Analysis
On this page, you can view either attrition rate or attrition count by using the slicer on the top right. This is made possible by using a calculation group
![Attrition Analysis](https://github.com/user-attachments/assets/76a87153-6a1b-4bfc-a9d1-7a80b26c97d7)

## Slicer Box
![Slicer Box](https://github.com/user-attachments/assets/f7b21f89-3496-4416-a926-2d663442b624)
