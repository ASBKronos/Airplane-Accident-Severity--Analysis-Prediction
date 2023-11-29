# Airplane Accident Severity: Analysis &Prediction
Machine Learning Project 

Problem Statement:
How severe can an airplane accident be? Flying has been the go-to mode of travel for years now; it is timesaving, affordable, and extremely convenient. According to the FAA, 2,781,971 passengers fly every day in the US, as in June 2019. Passengers reckon that flying is very safe, considering strict inspections are conducted and security measures are taken to avoid and/or mitigate any mis happenings. However, there remain a few chances of unfortunate incidents. Imagine you have got a project from leading airline. You are required to build Machine Learning models to anticipate and classify the severity of an airplane accident based on past incidents. With this, all airlines, even the entire aviation industry, can predict the severity of airplane accidents caused due to various factors and, correspondingly, have a plan of action to minimize the risk associated with them.

Data:
The dataset comprises of 1 files (Data is shared in the same folder) : ● Airplane_Accident_Data.csv: [10000 x 12 excluding the headers] contains all of the data.

Columns Description:
Accident_ID: Unique ID assigned to each row 
Cabin_Temperature: The last recorded temperature before the incident. Measured in degrees Fahrenheit 
Turbulence_In_gforces: The recorded/estimated turbulence experienced during the accident 
Accident_Type_Code: The type of accident (Factors the Type of Accident)
Control_Metric: An estimation of how much control the pilot had during the incident given the factors at play
Total_Safety_Complaints: Number of complaints from mechanics prior to the accident 
Days_Since_Inspection: How long the plane went without inspection before the incident  
Safety_Score: A measure of how safe the plane was deemed to be 
Violations: Number of violations that the aircraft received during inspections 
Severity: A description (4 level factor) on the severity of the crash [Target Variable]

Solution Approach:

Libraries Used:
• Pandas for data manipulation • NumPy for performing mathematical operations on the data • Matplotlib, Seaborn and Scikitplot for visualization • Sklearn for pre-processing and model building & evaluation
