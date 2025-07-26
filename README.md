As part of the Business Intelligence module in the Power BI intensive program at ITI, I developed a complete SSRS reporting system to deliver insights from both OLTP and OLAP data sources.
The project showcases interactive tabular, matrix, chart, and parameterized reports — integrating multiple data sources with a focus on usability, visual indicators, and export capabilities.

Key Features:
  Report Types:
•	Tabular Reports using the Report Wizard to display student information.
•	Matrix Reports to summarize sales quantities by ProductID and Salesman.
•	Chart Reports to visualize aggregated sales data.
•	Indicator Reports to visually represent student grades with color-coded status.
Logic & Expressions:
•	Used expressions to: Display student full name dynamically ,Show execution time and username in the footer and Render Page X of Y using built-in expressions.
•	Applied conditional formatting to highlight: Students with ages andGrades 
Parameters & Interactivity:
•	Implemented dropdown and multi-value parameters: Filter students by age range or department ID and Allow selecting multiple departments and display selections in header.
•	Enabled interactive sorting on Age.
•	Passed parameters into headers dynamically using expressions.
•	Created Linked Reports to navigate between department-level data and student grade reports.
Data Sources:
•	Connected to SQL Server database tables and Stored Procedures: One procedure fetched all course data and Another accepted @Age1 and @Age2 to filter student data.
•	Used SSAS Cube as a data source to create a report filtered by Year.

Technologies Used:
•	SSRS (SQL Server Reporting Services)
•	SQL Server
•	Stored Procedures (T-SQL)
•	SSAS (as data source)
•	Visual Studio Report Designer
