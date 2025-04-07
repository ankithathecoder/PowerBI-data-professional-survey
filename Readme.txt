Power BI Project – Data Professional Survey Analysis

This project is a Power BI dashboard built using a dataset from a survey of data professionals. The dashboard provides insights into various aspects such as job roles, programming languages, salaries, and satisfaction levels among professionals in the data field. Before visualization, extensive data cleaning and transformation were performed using Power Query.

📁 Project Structure

This repository includes:
- The original dataset: `data_set.xlsx`
- The transformed data used in Power BI: `transformed_data.xlsx`
- The Power BI project file: `Full_project.pbix`
- A screenshot of the final dashboard: `dashboard.png`
- This README file documenting the project.

🔧 Tools Used

- Power BI Desktop  
- Power Query for data transformation   

⚙️ Power Query Steps

1. Removed empty or unnecessary columns  
2. Cleaned the "Which title fits you most?" column by removing custom role specifications using "(" delimiter  
3. Cleaned the "Favourite programming language" column by removing text after ":" to generalize entries  
4. Transformed the salary column:  
   - Salary ranges like "100K-150K" were split using delimiters  
   - Removed characters like "K" and "-"  
   - Calculated the average salary from the range  
5. Grouped specific/custom entries under "Other" for consistency in columns like Country and Industry  

📊 Dashboard Highlights

- Total number of survey takers: 630  
- Average age of participants: 29.87  
- Most common job role: Data Analyst  
- Highest average salary: Data Scientist, followed by Data Engineer  
- Popular programming languages: Python, SQL, and R  
- Country with most responses: United States, followed by India  
- Work-life balance happiness index: 5.74 (out of 10)  
- Salary satisfaction happiness index: 4.27 (out of 10)  

📌 Notes
This project is inspired by a Power BI walkthrough by Alex The Analyst on YouTube. The dataset was sourced from his GitHub repository. While the original structure guided my process, I applied my own transformations, design choices, and added visual elements like a custom donut chart. 
