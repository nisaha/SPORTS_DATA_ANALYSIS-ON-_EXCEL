# SPORTS_DATA_ANALYSIS_ON_EXCEL

## PROJECT OBJECTIVE

We are a part of XYZ Co Pvt Ltd company who is in the business of organizing the sports events at international level. Countries nominate sportsmen from different departments and our team has been given the responsibility to systematize the membership roster and generate different reports as per business requirements. 

## Questions (KPIs)
#### TASK 1: STANDARDIZING THE DATASET

 - Populate the FULLNAME consisting of the following fields ONLY, in the prescribed format: PREFIX FIRSTNAME LASTNAME.{Note: All UPPERCASE) 
 - Get the COUNTRY NAME to which these sportsmen belong to. Make use of LOCATION sheet to get the required data
 - Populate the LANGUAGE_!poken by the sportsmen. Make use of LOCTION sheet to get the required data
 - Generate the EMAIL ADDRESS for those members, who speak English, in the prescribed format :lastname.firstnamel@xyz .org {Note: All lowercase) and for all other members, format should be lastname.firstname@xyz.com (Note: All lowercase)
 - Populate the SPORT LOCATION of the sport played by each player. Make use of SPORT sheet to get the required data

####  TASK 2: DATA FORMATING
 - Display MEMBER IDas always 3 digit number {Note: 001,002 ...,D2D,..etc)
 - Format the BIRTHDATE as dd mmm'yyyy (Prescribed format example: 09 May' 1986) 
 - Display the units for the WEIGHT column (Prescribedformat example: 80 kg)
 - Format the SALARY to show the data In thousands. If SALARYisless than 100,000 then display data with 2 decimal places else display data with one decimal place.In both c.ases units  should be thousands (k) e.g. 87670 -> 87.67 k and 12 250 -> 123.2 k

####  TASK 3: SUMMARIZE DATA - PIVOT TABLE (Use SPORTSMEN worksheet after attempting TASK 1)
• Create a PIVOT table in the worksheet ANALYSIS, starting at cell B3,with the following details: 
 - In COLUMNS; Group : GENDER.
 - In ROWS; Group : COUNTRY (Note: use COUNTRY NAMES).
 - In VALUES; calculate the count of candidates from each COUNTRY and GENDER type, Remove GRAND TOTALs.

####  TASK 4: SUMMARIZE DATA - EXCEL FUNCTIONS (Use SPORTSMEN worksheet after attempting TASK 1)
•  Create a SUMMARY table in the worksheet ANALYSIS,starting at cell G4, with the following details: 
 - Starting from range RANGE H4; get the distinct GENDER. Use remove duplicates option and transpose the data.
 - Starting from range RANGE GS; get the distinct COUNTRY (Note: use COUNTRY NAMES).
 - In the cross table,get the count of candidates from each COUNTRY and GENDER type.

####  TASK 5: GENERATE REPORT - PIVOT TABLE (Use SPORTSMEN worksheet after attempting TASK 1)
• Create a PIVOT table report in the worksheet REPORT, starting at cell A3, with the following information: 
 - Change the report layout to TABULAR form.
 - Remove expand and collapse buttons.
 - Remove GRAND TOTALs.
 - Allow user to filter the data by SPORT LOCATION.

## Process
 -	Verify data for any missing values and anomalies, and sort out the same.
 -	Made sure data is consistent and clean with respect to data type, data format and values used.
 -	Created pivot tables according to the questions asked.
