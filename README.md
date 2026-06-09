Instructions

You are provided with a data set titled ‘Lung Cancer Patient Health and Treatment Records’, which captures detailed information about patient demographics, diagnosis stage, lifestyle risk factors, comorbidities and treatment outcomes. 

 

Note: This data set was inspired by various healthcare-related learning resources and is not intended to represent real patient data.  

Dataset Link  
 
With the given data set, solve the following tasks using PySpark.

Task 1: Write a function that removes duplicate rows, ensures correct data types for numerical and date columns and converts all ‘yes’/ ‘no’ type fields into 1/0 format.  

Task 2: Write a function that adds a new column, treatment_duration_days, which calculates the number of days between the diagnosis and the end of treatment. Then, return the average treatment duration for each treatment type.  

Task 3: Write a function that returns the smoking_status group with the highest survival rate.  

Task 4: Write a function that returns the top three countries with the highest percentage of patients diagnosed in Stage IV.  

Task 5: Write a function that filters patients who:  

Are male  

Diagnosed in Stage III or IV  

Have a family history of cancer  

Are current smokers  

Have a BMI > 30  

Survived 

Return the average age and the percentage of these patients who had hypertension.
