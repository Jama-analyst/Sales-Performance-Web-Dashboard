# Sales-Performance-Web-Dashboard

# A detailed demonstration how to convert Excel Data into a Dynamic Web Dashboard using Claude AI
NB: Before you start with converting the data, make sure that the data is clean.

## To Create an Interactive Excel Dashbaord using Claude AI
- [X] Prepare the Sample Data
- Download your Data into CSV File
- Convert the CSV File into JSON File
- [X] Create a Web Dashboard with a Single Prompt using Claude AI
  
## Step 1 (Prepare the Sample Data)
- Download your Data into CSV File
   - Open your Excel File
   - then click on File Tab
   - click on Export
   - then on Change File Type
   - select CSV
   - then click on Save
  NB: Your CSV File will be saved under Documents/Desktop
![image](https://github.com/Jama-analyst/HR-Summary-Dashboard/blob/main/Data%20Loading.png)
## Step 2 (Prepare the Sample Data)
- Convert the CSV File into JSON File (Data Transformation Process)
Reason: Because JSON makes it easier to build a Web-based Dashboard
   - Open Google
   - search for CVS to JSON converter
   - select CSV.JSON
   - scroll down to the bottom then click on csv to json
   - two (2) screen will be dispalyed (a CSV and a JSON)
   - clear the default CSV option on the left side
   - then upload your CSV file from Desktop/Document
   - then click on Convert button
   - the JSON data will be generated on the right-side
   - click to Download
   NB: Your can save the downloaded JSON file in your Document/Desktop for easier access
![image](https://github.com/Jama-analyst/HR-Summary-Dashboard/blob/main/Data%20Loading.png)
## Step 3 (Create a Prompt using Claude AI)
   - Open Google
   - search for Claude AI
   - click on the official wwbsite on the top
   - once it's open
   - take a snapshot of one of your old Sales Dashboard
   - copy the snap and paste it into Claude AI
   - then ask Claude AI to create the Prompt
   - then press Enter
   - within moments, Claude AI will create a Prompt
   - once it's complete, copy and paste the Prompt in a Word Document for easier access
   - then save it under your Desktop/Documents
![image](https://github.com/Jama-analyst/HR-Summary-Dashboard/blob/main/Data%20Loading.png)
## Step 4 (Create a Web Dashboard with a Single Prompt using Claude AI)
   - Open Google
   - search for Claude AI
   - click on the official wwbsite on the top
   - once it's open
   - go back to your JSON converter
   - copy the JSON data
   - then paste it into Claude AI
   - then simply copy the Prompt and paste it into Claude AI
   - then press Enter
   - within moments, Claude AI will create your HTML-based Sales Performance Web Dashboard
   - once it's complete, download the file
     
  ## Step 5 (Create a Web Dashboard with a Single Prompt using Claude AI)
   - Open the Download File
   - next upload the JSON file by clicking on Choose JSON File icon
   - a screen will pop-up where you have saved your JSON File
   - then in minutes, the Dashboard with visuals will be dispayed
     
[Link Text] (URL)([https://github.com/Jama-analyst/Sales-Performance-Web-Dashboard/blob/main/sales_dashboard.html])

  NB:
  # Data is clearly dispalyed up to Records
  # Then you get four (4) useful Key Metrics, that gives you a quick Overview
  # Just below that you get seven (7) Premium Charts, beautifully visual.
   - once it's open
   - go back to your JSON converter
   - copy the JSON data
   - then paste it into Claude AI
   - simply copy the Prompt and paste it into Claude AI
   - then press Enter
   - within moments, Claude AI will create your HTML-based Sales Performance Web Dashboard
   - once it's complete, download the file
   
## Departmental Insights
The dashboard utilizes numerical identifiers for departments (1 through 6).
- [X] Employee Count:
   - Department 6 is the largest by a wide margin, employing over 400 individuals. Department 1 is the smallest, with fewer than 100 employees.
- [X] Income Distribution:
   - While Department 6 has the highest headcount, Department 4 appears to command the highest average monthly income, peaking at approximately 7,604.88 for male employees.
- [X] Gender Pay Parity:
   - In most departments, the average monthly income between male and female employees is closely aligned, suggesting equitable pay structures across the numerical divisions.

## Engagement Factors
The "Factors Affecting Job Experience" radar chart indicates multiple data points influencing the employee lifecycle. While specific labels are minimized, the distribution suggests that job experience is influenced by a balanced mix of internal factors rather than a single outlier.

## Key Insights & Observations
- [X] Stable Compensation: There is no drastic disparity in monthly income between the three departments, suggesting a standardized pay structure.
- [X] Experienced Workforce: With an average experience level exceeding 10 years, the organization likely benefits from high institutional knowledge.
- [X] Family Status: Nearly half the workforce is married, which may influence company benefit preferences (e.g. healthcare, parental leave).
- The organization possesses a highly experienced workforce (averaging nearly 14 years). This suggests high retention rates, though it may also indicate a need for succession planning as senior staff approach retirement.

## Sales Web Dashboard 
![image](https://github.com/Jama-analyst/Sales-Performance-Web-Dashboard/blob/main/sales_dashboard.html)

## Tech Stacks
- [X] IBM Cognos Analytics Tool
- [X] HR_DATASET.csv
- [X] Excel

## IBM Cognos Analystics Tool
Uploading HR_DATASET.csv File into IBM Cognos Analytics (via My Content)
- NB: I loaded the data into My Content to restrict public viewing.
![image](https://github.com/Jama-analyst/HR-Summary-Dashboard/blob/main/Data%20Loading.png)

## Dataset Understanding.
Understanding what data is available will be more helpful while doing analysis, before jumping on to the analysis one needds to get a good understanding of what data are available.

- [X] HR_DATASET.csv File Table:
- [ ]  The csv Files consist of the following Columns in the Table:
- Employee_ID	
- Gender
- Marital_Status
- Grade
- Count
- Job_Satisfaction
- MonthlyIncome
- MonthlyRate
- Age
- Job Type
- Job Experience
- Company_Environment
- TrainingTimesLastYear
- WorkLifeBalance
- YearsAtCompany
- YearsInCurrentRole
- Country
- Department_ID

## Data Module
- Data Module plays a vital role and is considered as the basement of report. All the visuals will be build upon the Data Module.
- Poor Data Module affects the over all performance of the report.
- Following Good practices of Data Module is a must.
- Created a Data Module that allowed me to fuse, clean, and shape data from disparate sources into a single, cohesive business view.
  ![image](https://github.com/Jama-analyst/HR-Summary-Dashboard/blob/main/Data%20Cleaning.png)

# Indepth Analysis (Comparison)
This report provides a comparative analysis of HR metrics across Australia (AU), the United Kingdom (UK), and the United States (US). While the organization maintains a consistent 60/40 gender split globally, regional differences emerge in workforce scale, compensation, and departmental focus.

## Workforce Scale & Experience
The UK represents the largest regional hub among the three, while Australia operates as a smaller, more specialized branch.
- [X] Metric:
- [ ] Total Employees: Australia (161), United Kingdom (752) , United States (557)
- [ ] Avg. Job Experience: Australia (Years - 13.05), United Kingdom (Years - 13.84), United States (Years - 14.29)
- [ ] Longevity: The US branch boasts the most seasoned workforce, averaging over 14 years of experience.
- [ ] Stability: All three regions show high tenure (13+ years), indicating strong employee retention across the globe.

## Compensation Analysis
Financial metrics show that the US branch leads in average earning power, while Australia sits at the lower end of the monthly income scale.
- Highest Earners: The United States has the highest Average Monthly Income (6.69K) and Monthly Rate (14.6K).
- The "Mid-Range": The UK follows closely with a 6.47K average monthly income.
- Regional Variance: Australia’s average income (6K) is roughly 10% lower than the US average, reflecting regional economic adjustments or different departmental compositions.

## Departmental Distribution
The primary focus of the workforce varies significantly by country:
- Australia: Operations are heavily concentrated in Department 5 (41 employees). Unlike other regions, Department 6 is nearly non-existent here.
- United Kingdom: A massive concentration in Department 6 (248 employees), making it the primary engine of the UK branch.
- United States: Shows a more balanced distribution but still leans toward Department 6 (156 employees) and Department 5 (123 employees).

## Diversity & Demographics
- [X] Gender Diversity
 - All three countries maintain a female-majority workforce, though the ratios fluctuate:
   - Australia: 62.1% Female / 37.9% MaleUnited Kingdom: 61.4% Female / 38.6% MaleUnited States: 57.5% Female / 42.5% Male (The most balanced ratio)
 - [X] Marital Status
 - Married employees are the largest demographic in all regions, peaking in the UK (47.1%).
 - Divorce rates are highest in Australia (27%), compared to the US (21.2%) and UK (22.1%).

## Key Findings & Anomalies
- [X] UK Income Spike:
      - In the United Kingdom, Department 3 male employees earn an outlier average of 9,479.45, the highest single departmental average across all three countries.
- [X] Australian Pay Gaps:
  - Australia shows the most visible departmental pay gaps, specifically in Department 2, where male income significantly outpaces female income (approx. 7.7K vs 6.3K).
- [X] US Experience:
   - The US has the most "senior" profile, which correlates with its higher average monthly income.

## HR Summary Dashboard (All Countries)
![image](https://github.com/Jama-analyst/HR-Summary-Dashboard/blob/main/HR%20Summary%20Dashboard%20(All%20Countries).png)

## HR Summary Dashboard - Australia
![image](https://github.com/Jama-analyst/HR-Summary-Dashboard/blob/main/HR%20Summary%20Dashboard%20(Australia).png)

## HR Summary Dashboard - United Kingdom
![image](https://github.com/Jama-analyst/HR-Summary-Dashboard/blob/main/HR%20Summary%20Dashboard%20(United%20Kingdom).png)

## HR Summary Dashboard - United States
![image](https://github.com/Jama-analyst/HR-Summary-Dashboard/blob/main/HR%20Summary%20Dashboard%20(United%20States).png)
