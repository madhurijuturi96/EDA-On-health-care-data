# EDA-On-health-care-data
## About the project

This project aims is to conduct a comprehensive Exploratory Data Analysis (EDA) on healthcare data using Python and Pandas. This  project provides valuable insights into appointment patterns and factors influencing appointment attendance in healthcare settings. By leveraging Python, Pandas, and data visualization tools, you will be  able to gain a nuanced understanding of the dataset's dynamics, which can inform decision-making and healthcare policy.



## About the dataset
I obtained dataset from [Medical appointments no shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments).  The dataset contains various attributes such as . The dataset contains 110.527 medical appointments its 14 associated variables (characteristics) such as patient ID, appointment ID, gender, scheduled day, appointment day, neighborhood, and various health-related indicators like hypertension, diabetes, alcoholism, and SMS received status . The most important one if the patient show-up or no-show to the appointment.

## Datapreprocessing: Data preprocessing includes cleaning the data and data transformation
     
			 1.Reading the dataset and modifying date and time into a standard form.
		
       2.Renaming columns for clarity and dropping columns with no significance.
			 
       3.Checking for missing values and performing data cleaning.

## Explanatory data analysis

       1.Calculating the count and percentage of appointments and no-shows.
		 
       2.Analyzing the distribution of patients across gender, age groups, and neighborhoods.
		 
       3.Investigating the impact of variables such as scholarship, hypertension, diabetes, and SMS reminders on appointment attendance.
		 
       4.Visualizing appointment patterns over the week to identify trends in appointment distribution.


## Python code
 The link for phython pandas are here: [EDA On healthcare](Medical_Appointments_Data_EDA.ipynb)


 ## Findings
   1.Female patients tend to take more appointments than male patients.
	 
   2.The ratio of no-shows to shows is nearly equal across age groups except for ages 0 and 1, where the show rate is 80%.
	 
   3.Each neighborhood shows an approximately 80% show rate.
	 
   4.Patients without scholarships have an 80% show rate, while those with scholarships have a 75% show rate.
	 
   5,Patients without hypertension have a 78% show rate, while those with hypertension have an 85% show rate.
	 
   6.Patients without diabetes have an 80% show rate, while those with diabetes have an 83% show rate.
	 
   7.Patients who did not receive SMS reminders have an 84% show rate, while those who did receive SMS reminders have a 72% show rate.
	 
   8.There are no appointments on Sundays, and appointments on Saturdays are significantly fewer compared to other weekdays.

 
