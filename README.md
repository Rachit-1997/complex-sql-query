# Employee Salary Analysis SQL Project

## 📌 Overview
This SQL project demonstrates advanced data analysis skills by examining employee salary histories to track:
- Current compensation levels
- Career progression through promotions
- Salary growth patterns over time
- Frequency and magnitude of salary changes

## 🗃️ Database Schema
Two tables form the foundation of this analysis:

1. `employees` table (Master data):
   - Employee ID (Primary Key)
   - Name
   - Join Date
   - Department

2. `salary_history` table (Transaction data):
   - Employee ID (Foreign Key)
   - Change Date
   - Salary Amount
   - Promotion Flag (Yes/No)

## 🔍 Key Analysis Features
1. **Current Salary Benchmarking** - Latest compensation for each employee
2. **Promotion Tracking** - Count of career advancements
3. **Salary Change Analysis**:
   - Maximum percentage hike received
   - Identification of employees who never had salary decreases
   - Average months between salary adjustments
4. **Growth Rate Ranking** - Employees ranked by overall salary growth since joining

## 🛠️ Technical Skills Demonstrated
- Complex SQL queries with Common Table Expressions (CTEs)
- Window functions for advanced analytics
- Precise date calculations
- Percentage change computations
- Data aggregation and ranking

## 🚀 How to Run This Analysis
1. Execute `schema.sql` to create the database tables
2. Run `data.sql` to populate with sample data
3. Execute `analysis.sql` to generate the complete analysis

## 📊 Sample Insights
The analysis reveals:
- Employee growth trajectories
- Department-wise compensation patterns
- Most frequent promotion recipients
- Salary change trends over time

## 🤝 Potential Use Cases
- HR Analytics
- Compensation Benchmarking
- Retention Risk Analysis
- Career Progression Studies
 
