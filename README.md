Project Overview:
The dataset is a mock representation of a hospital management database.
It contains six tables: Appointments, Bills, Doctors, Medications, Patients and Treatment.
The goal of this project is to answer some important questions regarding hospital management which would aid in various ways.

Tools used:
SQL (Data entry and query)
Power BI (Data visualisation)

Questions:
1. How has appointment volume changed over the past 6 months?
-> Number of appointments has drastically increased and more appointments are completed and scheduled.

2. Which days or months have the most appointments scheduled?
-> Tuesday and Saturday has the most number of appointments.
   February has the most number of appointments.

3. What percentage of appointments were cancelled or missed?
-> 49% of appointments were cancelled or missed. There is something very wrong with this fake hospital. 

4. Which doctor has handled the most appointments?
-> Salomi Ridulfo who is an Orthopedics has handled the most appointments.

5. Which specialization has the highest patient load?
-> Pediatrics have the highest patient load.

6. What is the total revenue from completed appointments?
-> 153.03k Bucks is the total revenue. This hospital is struggling.

7. What is the average bill amount per patient?
-> 1530.25 Bucks is the average bill amount.

8. How many patients visited more than once in the last 3 months?
-> There are 9 patients who have visited more than once in the last 3 months.

9. Which gender/age group visits most frequently?
-> The group that visits most frequently are females who are 50 and above.

10. What are the top 5 reasons for appointments?
-> Injury, Asthma, Checkup, Hypertension, Routine check.

11. Is there any seasonality in certain conditions (e.g. asthma, fever)?
-> There is seasonality present for asthma. Not much for fever.

12. Missed appointment rate by doctor.
-> There are 16 doctors who have a 100% miss rate. This is dire.

Insights:
Appointment Trends
Appointment volume has grown significantly over the past 6 months, with a rise in both scheduled and completed visits — indicating improving operational activity or patient demand.

Tuesdays and Saturdays are the busiest days of the week, with February being the peak month for appointments.

Missed & Cancelled Appointments
A staggering 49% of all appointments were missed or cancelled, suggesting serious operational or patient compliance issues.

16 doctors had a 100% missed appointment rate, raising concerns about scheduling accuracy, patient communication, or data quality.

Doctor & Specialization Insights
Dr. Salomi Ridulfo (Orthopedics) handled the most appointments — a standout performer in patient load.

Orthopedics emerged as the busiest department, attracting the highest number of appointments across the hospital.

Revenue & Billing Analysis
The hospital earned a total revenue of 40,547.5 Bucks from completed appointments, which is modest for a facility of this size.

The average bill per patient is 1,530.25 Bucks, suggesting either limited service offerings or underbilling.

Patient Behavior Patterns
Only 9 patients visited more than once in the last 3 months, which could imply low retention or a preference for one-time visits.

The most frequent visitors are females aged 50 and above, indicating a demographic segment with recurring or chronic care needs.

Medical Trends
Top 5 reasons for appointments are: Injury, Asthma, Checkup, Hypertension, Routine check — reflecting both acute and chronic health needs.

Clear seasonal spikes in Asthma cases were observed, while Fever did not show strong seasonality.

Files Explained:
schema.sql : Defines the structure of tables.
mock_data.sql : Generates sample data
analysis_queries.sql : actual SQL logic used to find insights.
