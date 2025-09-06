# Martins Adedoyin's Data & Business Analyst Portfolio

<img src="https://github.com/adedoyinmartins1/Martins-Adedoyin/blob/main/martins%20pix.jpg" alt="Headshot" width="350">

**Hello! I’m Martins Adedoyin, an entry-level data analyst with a specialization in Excel. I have mastered various formulas, including IF, IFS, COUNTIF, COUNTIFS, VLOOKUP, XLOOKUP, TEXT, and TRIM. I am passionate about cleaning messy datasets and delivering clear, actionable insights to drive business success. After completing my Excel training, I plan to learn Power BI, SQL, and data storytelling to create impactful strategies. This portfolio showcases my projects and skills, demonstrating my commitment to becoming a proficient data analyst.**
 
### About Me
- **Background**: Self-taught data analyst with 3+ months of experience in Excel, focusing on data analysis and visualization. I started my journey in July 2025 and am excited to grow in the field.
- **Skills**:

  <img src="https://github.com/adedoyinmartins1/Martins-Adedoyin/blob/main/excel%20logo1.jpg" alt="Headshot" width="100">: VLOOKUP, HLOOKUP, COUNTIFS, IFS, XLOOKUP, TRIM, TEXT

  - **Soft Skills**: Communication, Attention To Details, Time Management
  - Data Analysis: Data cleaning, summarization
  - **Future Learning**:

    <img src="https://github.com/adedoyinmartins1/Martins-Adedoyin/blob/main/Power-Bi-Logo.png" alt="Headshot" width="200"> <img src="https://github.com/adedoyinmartins1/Martins-Adedoyin/blob/main/sql-logo.webp" width="100">
    
- **Location**: Ilorin, Nigeria
- **Goals**: To become a proficient data analyst skilled in Power BI, SQL, and data storytelling for business impact.

## Featured Projects

### Excel-Logical Assignment-Gender and Country-Based Purchase Counts Using COUNTIFS

<img src="https://github.com/adedoyinmartins1/Martins-Adedoyin/blob/main/Excel%20Logical%20Assignment%201%20screenshot.png" width="350">

- **Data Description**: The dataset is a tabular structure with 501 rows of sample order data, including the following columns:

  •	Customer¬_#: Unique customer identifier.

  •	Full Name: Customer's name.

  •	Gender: Female or Male.

  •	City: Customer's city.

  •	Country: Customer's country.

  •	Phone Number: Contact number (some marked as "Not Found").

  •	Products: Product name (e.g., Product 1, Product 10).

  •	Quantity: Number of units purchased (not used in counting but available for potential extensions).
  
- **Technology**: Excel (COUNTIFS)
- **Methodology**: I followed a structured approach to complete the assignment:
1.	Data Preparation: 
- Imported the dataset into Sheet1 named it (Task).
- Created 2 new sheets named them (Female category and Male category) respectively.
- In the 2 sheets, I listed unique countries in Column A. I was able to do that by using the duplicate remover function by highlighting the data range and press Alt + A + M then Enter.
- Listed out all the products from 1-10 in the other Columns.
2.	Formula Application: Used COUNTIFS to count rows in Sheet1 meeting multiple criteria: matching gender and country e.g.
General COUNTIFS syntax: =COUNTIFS(range1, criteria1, range2, criteria2, ...)
Specific formulas =COUNTIFS(CountIFS_Test!$C$2:$C$501,CountIFS_Test!$C$2,CountIFS_Test!$E$2:$E$501,A2,CountIFS_Test!$H$2:$H$501,CountIFS_Test!$H$3) this was formula was specifically used to obtain the result for Product 1 in the female category, and the same approach was applied for all the products. 
3.	Validation: Ensured absolute references ($/f4) key for fixed ranges.
4.	Output Presentation: Formatted the Summary sheet with bold headers, borders, and conditional formatting

- **Files**: [Excel-Logical Assignment-Gender and Country-Based Purchase Counts](https://github.com/adedoyinmartins1/Martins-Adedoyin/blob/main/Excel_Logical%20Assignments1_Gender%20and%20Country_Based%20Purchase%20Counts.xlsx)
- **Link**: [Project Repository](https://github.com/adedoyinmartins1/Excel-Logical-Assignment-Gender-and-Country-Based-Purchase-Counts-Using-COUNTIFS)


### Excel Logical Functions Project-Workforce Analysis Assignment

<img src="https://github.com/adedoyinmartins1/Martins-Adedoyin/blob/main/2nd%20Assignment%20screenshot.png" width="350">

- **Data Description**:
The dataset is structured in an Excel workbook named "Excel-Logical Assignment.xlsx" with two sheets:

•	**Task-Workforce_Planning_and_Pro: Raw data including**:
  - Employee Name (e.g., Alice, Bob)
  - Department (IT, Sales, Marketing, HR, Finance)
  - Performance Score (1-10)
  - Salary (numeric, in USD)
  - Years of Experience (0-20)

•	**Logical_workout**: Extended sheet with derived columns (as per assignment tasks). 

Sample data preview (first few rows):

**Employee Name	Department	Performance Score	Salary	Years of Experience**
Alice	IT	7	$66368	2
Grace	IT	4	$36783	8
Hannah	Sales	8	$71914	7
Eva	Sales	5	$100507	0
Bob	Marketing	7	$109026	5

- **Technologies**: Excel (IF,IFS and NESTED IF)
- **Files**: [Excel Logical Functions Project-Workforce Analysis Assignment](https://github.com/adedoyinmartins1/Excel-Logical-Functions-Project--Workforce-Analysis-Assignment/blob/main/Digital_World_Logical_Test.xlsx)
