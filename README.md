# PALMORIA-GROUP-ANALYSIS-
## INTRODUCTION
### Palmoria Group, a manufacturing company has come under scrunity for gender inequality across its three regional operations. With media headlines labeling the company as a "Manufacturing Patriarchy", executive leadership is keen to uncover and resolve any HR- related disparities, especially those tied to gender. As a result, the CHRO has commisssioned a detailed analytics review using internal employee data.
## OBJECTIVES
### This analysis aims to: 
#### 1. Evaluate gender distribution across the company.
#### 2. Assess fairness in employee performance ratings.
#### 3. Analyse salary structure for potential gender pay gaps.
#### 4. Ensure compliance with a newly mandated $90,000 minimum wage.
#### 5. Calculate and allocate employee bonuses based on performance ratings.
#### 6. Present clear, visual insights to aid executive decision making.

## DATA PREPARATION AND CLEANING
### Two datasets were provided: 
- Employee Data (Palmoria Group emp-data.csv)
- Bonus Rules (Palmoria group Bonus Rules.xlsx)
### Cleaning Steps:
#### 1. Generic Gender: Employees with missing gender were assigned a generic label "Undisclosed".
#### 2. Row Exclusions:
- Employees without a salary (no longer with company) were excluded.
- Departments labeled "NULL" were also removed.
#### 3. Bonus Matching:
- Each employee was matched to a bonus percentage based on their performance rating, as per the bonus rules

## ANALYSIS AND VISUALS IN POWER BI
### 1. GENDER DISTRIBUTION
- Visual 1: Clustered Bar Chart
- X- Axis: Department
- Y- Axis: Count of Region
- Legend: Gender

- Visual 2: Clustered Bar Chart
- X- Axis: Region
- Y- Axis: Count of Department
- Legend: Gender
### 2. RATINGS BY GENDER
- Visual: Clusteed Column Chart
- X- Axis: Rating
- Y- Axis: Count of Department
- Legend: Gender
### 3. Gender Pay Gap
- Visual 1: Matrix
- Visual 2: Matrix
- Visual 3: 100% stacked column chart
### 4. Salary Band Compliance
- Visual: Pie Chart
- Legend: Compliance check (Created column)
- Values: Sum of salary
### 5. Bonus and Total Compensation
- Visual 1: Stacked bar chart
- Visual 2: Card
- Visual 3: Card
