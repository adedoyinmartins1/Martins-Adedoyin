# Excel Logical Assignmen- Gender and Country Based Purchase Counts Using COUNTIFS


### Project Overview
This project is part of my Microsoft Excel course aimed at aspiring data analysts. It involves analyzing a sample dataset of customer orders to gain insights into purchasing behavior, segmented by gender and country. The dataset, provided by my trainer, contains anonymized records of customer details, order dates, products, and quantities.
Using Excel's COUNTIFS function, I calculated the number of purchases (i.e., order instances) made by female and male clients from each unique country listed. This exercise demonstrates my ability to apply logical formulas for multi-criteria counting, data summarization, and basic segmentation analysis. I compiled the results in a separate sheet within the same workbook for clear presentation.
This assignment highlights foundational skills in data manipulation and reporting, which are essential for real-world data analysis roles.

### Objective
•  **Primary Objective**: Use the COUNTIFS formula to count product purchases (order rows meeting specific criteria) segmented by: 
•	Gender (Female or Male)
•	Country: This analysis reveals the distribution of purchases across demographics and geographies.
•  **Secondary Goals**: 
•	Practice data organization
•	Enhance formula error-handling
•	Create a summarised output sheet to effectively showcase analytical findings

### Scope of the Analysis
•	Data Coverage: The analysis is limited to the provided dataset, which includes 500 order records. It covers customers from 46 unique countries : such as USA, Japan, Vietnam, Ghana, Sudan, China, Denmark, Russia, Brazil, UAE E.T.C.
•	Inclusions: 
o	Counting order instances (rows) as proxies for purchases.
o	Segmentation by gender and country only.
o	Use of COUNTIFS for conditional counting.
•	Exclusions: 
o	No summation of quantities (as the assignment specified COUNTIFS, not SUMIFS).
o	No analysis of other variables like city, product type, or order date trends.
•	No external data integration or advanced visualizations (e.g., charts were optional but not required).
•	 Assumptions: Each row represents a unique purchase event. Repeated customers (e.g., those with multiple orders) are counted separately per order. "Not Found" phone numbers were ignored as they don't affect the core criteria.
This scope keeps the analysis focused on the assignment's requirements while demonstrating targeted Excel proficiency.

###Data Description
The dataset is a tabular structure with 501 rows of sample order data, including the following columns:
•	Customer¬_#: Unique customer identifier.
•	Full Name: Customer's name.
•	Gender: Female or Male.
•	City: Customer's city.
•	Country: Customer's country. 
•	Phone Number: Contact number (some marked as "Not Found").
•	Products: Product name (e.g., Product 1, Product 10).
•	Quantity: Number of units purchased (not used in counting but available for potential extensions).

### Methodology
I followed a structured approach to complete the assignment:
1.	Data Preparation: 
o	Imported the dataset into Sheet1 named it (Task).
o	Created 2 new sheets named them (Female category and Male category) respectively.
o	In the 2 sheets, I listed unique countries in Column A. I was able to do that by using the duplicate remover function by highlighting the data range and press Alt + A + M then Enter.
o	Listed out all the products from 1-10 in the other Columns.
2.	Formula Application: 
o	Used COUNTIFS to count rows in Sheet1 meeting multiple criteria: matching gender and country e.g.
o	General COUNTIFS syntax: =COUNTIFS(range1, criteria1, range2, criteria2, ...)
Specific formulas =COUNTIFS(CountIFS_Test!$C$2:$C$501,CountIFS_Test!$C$2,CountIFS_Test!$E$2:$E$501,A2,CountIFS_Test!$H$2:$H$501,CountIFS_Test!$H$3) this was formula was specifically used to obtain the result for Product 1 in the female category, and the same approach was applied for all the products. 
3.	Validation: 
•	Ensured absolute references ($/f4) key for fixed ranges.
4.	Output Presentation: 
•	Formatted the Summary sheet with bold headers, borders, and conditional formatting

### Challenges and Learnings
•	Challenges: Ensuring correct range references to avoid #VALUE! Errors.
•	Learnings: Gained proficiency in COUNTIFS for multi-condition analysis, which is scalable for real datasets. Understood the importance of absolute vs. relative references when dragging formulas. This built my confidence in logical functions for segmentation tasks. 

### Conclusion
 This assignment reinforced essential Excel skills for data analysis, particularly in using COUNTIFS for conditional counting. By segmenting purchases by gender and country, I demonstrated how simple formulas can uncover demographic patterns. This project serves as a building block in my portfolio, showcasing my progress in the course and readiness for more complex analyses. Future extensions could include SUMIFS for quantity totals. 
 
### Attachments/Links
•	Excel File: Download Purchase_Analysis_Assignment.xlsx – Includes raw data, formulas, and summary.
•	Screenshots: Embedded images of key sheets.
 

