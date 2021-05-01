# Medical Case Study
This is a case study about the financial fines paid by doctors working in research dept of a company.

### Data Description
There are two datasets in this case study. 'Emails sent' dataset contains the doctor names, the date at which email stating the fines was sent and the office at which the doctors worked. Each row in this dataset represents an email sent to a doctor. 'Fines paid by doctors' dataset contains the online and cash fines. Some doctors paid both fines in cash as well as online. </br>

**Dataset 1: Emails sent**

![Image!](https://github.com/ushashwat/Medical-Fines-Case-Study/blob/main/images/mail_data.png) </br>

Key | Understanding
----- | -----
first_name | First name of doctor
last_name | Last name of doctor
name_middle | Middle name of doctor
mail_sent_date | Date on which email stating the fine was issued
office | Office where research was conducted

**Dataset 2: Fines paid by doctors**

![Image!](https://github.com/ushashwat/Medical-Fines-Case-Study/blob/main/images/fine_data.png) </br>

Key | Understanding
----- | -----
org_indiv | Name of doctor and organization
first_name | First name of doctor
last_name | Last name of doctor
city | City where research was conducted
state | State where research was conducted
category | Research category
cash_fine | Fine paid by cash
online_fine | Fine paid online

### Analysis
Using the given data, perform the following operations and obtain the result:
* Standardise the mail_sent_date column values to YYYY-MM-DD standard date format
* The year in which maximum number of emails were sent to doctors
* Total fine paid per Office
* Get the highest total fine and lowest total fine paid per state
* The least 2 states that had to pay minimum 'online' fine
* The number of doctors that contributed to the state having highest 'cash' fine
* Get the top 5 average fine paid per state and category
