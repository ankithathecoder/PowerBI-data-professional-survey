# 📊 Power BI Project – Data Professional Survey Analysis

## 📌 Project Overview  
This project features a Power BI dashboard built using a dataset from a survey of data professionals. The dashboard uncovers insights into various aspects such as job roles, programming languages, salaries, and satisfaction levels among professionals in the data field. Before creating the visuals, extensive data cleaning and transformation were performed using Power Query.

---

## 📁 Project Structure  
This repository includes the following files:

- `data_set.xlsx` – The original dataset  
- `transformed_data.xlsx` – Data after cleaning and transformation  
- `Full_project.pbix` – The Power BI report file  
- `dashboard.png` – Screenshot of the final dashboard  
- `README.md` – Project summary and documentation  

---

## 🔧 Tools Used  
- **Power BI Desktop** – For building the dashboard  
- **Power Query** – For data cleaning and transformation  

---

## ⚙️ Power Query Steps  

1. Removed empty and irrelevant columns  
2. Cleaned the **"Which title fits you most?"** column by removing custom role specifications using the `(` delimiter  
3. Cleaned the **"Favourite programming language"** column by removing text after `:` to generalize entries  
4. Transformed the **Salary** column:  
   - Split salary ranges like `100K-150K` using delimiters  
   - Removed characters like `K` and `-`  
   - Calculated the average salary for each entry  
5. Grouped uncommon or custom entries under `"Other"` in **Country** and **Industry** columns for consistency  

---

## 📊 Dashboard Highlights  

- 👥 **Total survey participants**: 630  
- 🎂 **Average age**: 29.87  
- 💼 **Most common job role**: Data Analyst  
- 💰 **Highest average salary**: Data Scientist, followed by Data Engineer  
- 🖥️ **Popular programming languages**: Python, SQL, and R  
- 🌍 **Top countries by participation**: United States, followed by India  
- 😊 **Work-life balance index**: 5.74 / 10  
- 💸 **Salary satisfaction index**: 4.27 / 10  

---

## 📝 Notes  
This project is inspired by a Power BI tutorial by **Alex The Analyst** on YouTube. The dataset was sourced from his GitHub repository. While the walkthrough served as a reference, the cleaning steps, visual design, and some transformations were customized. Additional visual elements, such as a donut chart, were added to enhance presentation.

---

## ✅ Conclusion  
This project demonstrates the use of Power BI for end-to-end analysis—from data transformation in Power Query to creating interactive visuals that present clear and meaningful insights into the data professional landscape.
