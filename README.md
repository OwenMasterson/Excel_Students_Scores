# Excel_Students_Scores 
This project analyses student exam results across English, Mathematics, and Science to evaluate academic performance and assign achievement categories. Using Excel formulas and structured data processing, the dataset calculates averages, identifies highest scores, and classifies each student into performance tiers for clear, actionable insights.

# Executive Summary
The dataset provides a structured overview of student performance by combining raw subject scores with automated calculations that highlight overall achievement. By computing each student’s average score and highest subject score, the analysis enables quick comparison across learners and supports data‑driven decisions such as identifying top performers or students who may need additional support. An award‑classification formula further enhances the dataset by grouping students into categories—Star Performer, Solid Achiever, On the Rise, and Needs Support—based on their average score thresholds.

# Tools Used
## Microsoft Excel
 Excel was used as the primary tool for data entry, calculation, and categorisation. Key features leveraged include:
* Cell formulas for automated calculations
* Conditional logic (IF statements) for award assignment
* Tabular formatting for clean data organisation
* Built‑in functions such as AVERAGE and MAX (if used elsewhere in the workbook)
* Excel provides an accessible and efficient environment for performing lightweight analytics without requiring programming.

# Key Processes
### 1. Data Entry and Structuring
The dataset includes the following columns:

Student Name

English Score

Mathematics Score

Science Score

Average Score

Highest Score

Award Category

Each row represents one student.

### 2. Calculating the Average Score
The average score is computed using the three subject marks.
Example formula (not shown in the screenshot but implied):

### Code:
=AVERAGE(B2:D2)
### 3. Identifying the Highest Score
The highest score across the three subjects is calculated using:

### Code:
=MAX(B2:D2)
### 4. Award Classification Using IF Logic
The award category is determined using a nested IF formula based on the student’s average score:

### Code:
=IF(E2>=80,"Star Performer",
   IF(E2>=70,"Solid Achiever",
      IF(E2>=60,"On the Rise","Needs Support")))
This formula assigns each student to a performance tier, making the dataset more interpretable and actionable.

# Summary of Insights
*Students scoring 80+ on average are recognised as Star Performers.
*Those in the 70–79 range are labelled Solid Achievers.
*Averages between 60–69 fall under On the Rise.
*Scores below 60 indicate students who Need Support.

This structured approach transforms raw exam scores into meaningful insights that can support educators in tracking progress, identifying strengths, and planning interventions.

<img width="1161" height="443" alt="Screenshot 2026-02-10 160335" src="https://github.com/user-attachments/assets/67b7e4ad-7170-44ea-a0c0-bacd33e04b81" />
Excel Link: https://excel.cloud.microsoft/open/onedrive/?docId=5E38D8AD1B1DBB11%21sa524c31c502b4993a22fd89e80db8f0e&driveId=5E38D8AD1B1DBB11
