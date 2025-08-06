# Employee-Management-SQL-Project

This project simulates a complete Employee Management System using SQL and provides advanced analytical queries for HR and business insights such as salary analysis, department-wise headcount, payroll processing, leave tracking, and qualification mapping.

---

## Tables Included
- Employees  
- Departments  
- Job_Roles  
- Qualifications  
- Employee_Qualifications  
- Leave_Records  
- Payroll  
- Bonus  

---

## Objective

To design and implement a relational database system for managing employee information within an organization.  
The system is built to:
- Store employee details, job roles, qualifications, and payroll information.  
- Track leaves and bonuses.  
- Generate meaningful business insights through SQL queries.  
- Ensure data integrity through proper use of foreign key constraints and normalization.

---

## Technologies Used
- SQL (MySQL / PostgreSQL)  
- DBMS: MySQL (recommended)

---

## Sample Business Queries
- Total number of employees  
- Department-wise employee count  
- Top 5 highest-paid employees  
- Average salary per department  
- Total monthly payroll  
- Leave patterns over the years  
- Qualifications required per position  
- Employees with most leave days  
- Year-wise employee promotions  

---

## Folder Structure
employee-management-sql/
│
├── schema/
│ ├── create_tables.sql # All CREATE TABLE statements
│ └── insert_data.sql # INSERT INTO statements for mock data
│
├── queries/
│ ├── employee_insights.sql # Count, salaries, top earners
│ ├── department_analysis.sql # Role, department-wise salary allocation
│ ├── qualification_analysis.sql
│ ├── leave_patterns.sql
│ ├── payroll_analysis.sql
│ └── performance_growth.sql
│
├── ERD.png # Optional: ER diagram of the system
├── README.md # Project overview and usage instructions

yaml
Copy
Edit

---

## ✅ How to Run

1. Set up a SQL environment (e.g., MySQL Workbench or pgAdmin)  
2. Run `schema/create_tables.sql`  
3. Run `schema/insert_data.sql`  
4. Execute any SQL script from the `queries/` folder to perform analysis  

---

## Key Insights from the Project
- 60 unique employees tracked across departments  
- Finance department has the highest employee count and salary allocation  
- Average department salaries vary, showing compensation strategy  
- HR roles require the most qualifications  
- 2024 saw the highest number of leaves taken  
- Total payroll processed = ₹2,778,000  
- Average net salary after deductions = ₹874,711  
- 2019 had the most employee promotions  

---

## 👨‍💻 Author

**Saideepu Balaraju**
