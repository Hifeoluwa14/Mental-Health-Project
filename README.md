# Depression Analysis Using Excel

This project involves data cleaning, preprocessing, and exploratory analysis of a large dataset (140,700 entries) to investigate the prevalence and contributing factors of depression among students and working professionals. All analysis and transformations were performed using Microsoft Excel.

## Data Cleaning and Preprocessing
1. Dataset Preparation: Copied the raw dataset into a new sheet for backup and safe handling.
2. Null Value Treatment: Identified and handled missing values in key columns:
  * Profession, Academic Pressure, Work Pressure, CGPA, Study Satisfaction, Work Satisfaction, Dietary Habits, Degree, Financial Stress.
  * Replaced null values in Financial Stress with the column's average.
  * Filled null values in Profession based on Working Professional or Student classification.
  * For CGPA: Students Filled with the average CGPA and Non-students Marked as Not a Student.
3. Data Quality Improvements:
  * Checked for and found no duplicate rows.
  * Cleaned and standardized Dietary Habits column. Unclear entries marked as Unknown Habit.
  * Cleaned the City column by fixing typos and replacing invalid entries with Unknown.
  * Cleaned Degree entries.
4. Created new columns:
  * Work/Academic Pressure (combined Work Pressure and Academic Pressure)
  * Work/Study Satisfaction (combined Work Satisfaction and Study Satisfaction)
5. Removed now-redundant columns: Work Pressure, Academic Pressure, Study Satisfaction, Work Satisfaction

## Key Findings

**Depression Statistics**: 
  * Total: 140,700 individuals
  * Depressed individual: 25,567(18.2%)

        
It was observed that depressed individuals showed higher work/academic pressure, higher financial stress, more work/study hours and lower work/study satisfaction.


<img width="825" height="40" alt="Depressed" src="https://github.com/user-attachments/assets/8892f759-95ce-4986-aa39-a6ea85c7c805" /><br><br>


**Professions**:
  * Students: 16,336 depressed, about 60% of all students
  * Working Professionals: 9,231 depressed, about 8% of all professionals.
    
<img width="1344" height="993" alt="Picture1" src="https://github.com/user-attachments/assets/d0e71b6f-149a-4fc3-b3b3-7e973ca73608" />


Students also reported more suicidal thoughts than working professionals.<br>
<img width="395" height="102" alt="Suicidal thoughts" src="https://github.com/user-attachments/assets/0c79b301-3711-47b1-a8ec-c9f6b968ee1b" /><br><br>


**CGPA & Depression**:
 * First Class: 3,587 students 
 * Second Class Upper: 5,534 students
 * Second Class Lower: 4,212 students
 * Third Class: 3,003 students
<img width="1310" height="993" alt="Picture2" src="https://github.com/user-attachments/assets/389525db-8647-467b-9983-4abc1b5fced8" /><br><br>

**Education Level**:<br>
Class 12 students make up ~30% of all depressed students (7,549 students)<br>
Next highest group: B.Ed students with 1,505 (~6%)<br>
<img width="2763" height="1659" alt="Picture2" src="https://github.com/user-attachments/assets/e6e858ac-c0a8-4034-ac7c-edbcdd3732a4" /><br><br>


**Gender and Depression**:
 * Females: 17.82% depressed
 * Males: 18.46% depressed

<img width="389" height="104" alt="Gender Depression" src="https://github.com/user-attachments/assets/d8910b7d-bfe7-46d7-901e-cc130fbe6ab7" /><br><br>
**Age and Depression**:
 * Teenagers: 67.83% of 6,555 are depressed
 * Young Adults: 35.33% of 56,727 are depressed
 * Age 40–65: Only 1.40% of 77,418 are depressed

<img width="391" height="146" alt="Age Depression" src="https://github.com/user-attachments/assets/ecb77665-a405-47b8-95b6-29babd7e04a1" /><br><br>


## Tools Used
Microsoft Excel
(Data cleaning, transformation, pivot charts, conditional formatting, and data visualization)<br><br>
## Conclusion
* Students shows 7.5x higher depression rates than working professionals
* Teenagers are nore vulnerable to depression.
* Work/Academic Pressure, Work/Study Satisfaction, Work/Study hours and Financial stress are significant factors for depression<br><br>
## Recommendation
There is need for targeted mental health for students populations, particularly teenagers.

