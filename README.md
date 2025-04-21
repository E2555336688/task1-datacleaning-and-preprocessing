# task1-datacleaning-and-preprocessing
This repository contains source code for  preparing raw data for analysis, making it reliable and suitable for further processing.
The first step in data analysis is data cleaning and preprocessing, it helps to transform a raw data into a useful data which can be used for further analysing process.
For that first we have to upload our dataset and load it using pandas. Here I used colab notebook to run codes.
The dataset is downloaded from Kaggle titled as Medical Appointment No Shows.
Next I changed the index numbering to start from 1, previously it was from 0. Starting from 1 is easy for further analysing process.
After this we begin with data cleaning and preprocessing.
First we deal with missing values and duplicate values. 
If there are missing values in our data set, either remove that row or fill it with an appropriate value. Duplicate values can be droped to avoid disturbance in further steps.
In this case there is no missing values and duplicate values present.
Check data types of each columns and convert it to appropriate data types.
I changed the column named ScheduledDay and AppointmentDay to datetime data type, changing it from object data type.
Before that the date and time is standardized into dd-mm-yyyy HH:MM:SS .
For better understanding of our dataset value count of columns will help. This can also helps in finding a solution to our questions.
After data cleaning and preprocessing we can use this dataset to retrive answers for questions we arise in the beggining of the project.
For example, we can find the reasons behind no show up of patients by analyzing suitable variables.
