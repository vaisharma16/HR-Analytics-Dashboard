
# 🧑‍💼 HR Analytics Dashboard – Employee Attrition Analysis

This project is a **Power BI dashboard** designed to analyze and visualize employee attrition data. It helps HR departments and stakeholders identify trends, patterns, and key drivers behind workforce attrition to make data-informed decisions.

![Dashboard Screenshot](https://github.com/vaisharma16/HR-Analytics-Dashboard/blob/main/Dashboard.png)

---

## 📊 Dashboard Features

- **Total Employees**: 1,470  
- **Total Attrition Cases**: 238  
- **Attrition Rate**: 16.08%  
- **Average Age**: 36.92 years  
- **Average Monthly Income**: ₹6.50K  
- **Average Tenure**: 7.01 years  

### Breakdown Visuals:
- Attrition by **Gender**, **Age Group**, **Business Travel**, **Salary Slab**
- Attrition count across **Departments**, **Education Fields**, **Marital Status**, and **Job Roles**
- Attrition trends by **Years at Company**
- Interactive **slicers** for all key attributes (Department, Age Group, Education, Salary, etc.)
---

🔍 Project Description: HR Analytics Dashboard – Employee Attrition Analysis (Power BI)
- Built an interactive Power BI dashboard to analyze and visualize employee attrition data for strategic HR decision-making.

✅ Key Highlights:

- Visualized attrition across dimensions like age, gender, salary, education, department, and job roles

- Used DAX measures to calculate dynamic KPIs like Attrition Count and Attrition Rate

- Integrated slicers for interactive exploration by business travel, salary slab, marital status, and more

- Identified key attrition patterns to support employee retention strategies.

---

## 📐 DAX Measures Used

Two DAX formulas were implemented for metric calculation:

```
AttritionCount = IF(HR_Analytics[Attrition] = "Yes", 1, 0)

AttritionRate = SUM(HR_Analytics[AttritionCount]) / SUM(HR_Analytics[EmployeeCount])
```

These measures power dynamic, filter-responsive attrition KPIs across the dashboard.

---

## 📁 Dataset Information

- **Source:** Kaggle – HR Analytics Dataset  
- **Author:** Anshika2301  
- **Description:** Includes anonymized employee records with features such as age, gender, department, education, salary, travel, years at company, and attrition status.

---

## 🛠 Tools & Technologies

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Basic ETL transformations within Power BI

---

## 📌 Project Objective

To build an interactive, insightful HR dashboard that:
- Highlights attrition hotspots
- Reveals key demographic and job-related factors affecting attrition
- Assists HR in designing proactive retention strategies

---

## 📚 References & Credits

- 🎥 **Tutorial Video:** HR Analytics Dashboard – Power BI  
  by Colorstech Training (Slidescope) [Youtube video](https://www.youtube.com/watch?v=tGrEGku646A&t=2215s)
- 📂 **Dataset:** Kaggle – HR Analytics Dataset  [Dataset](https://www.kaggle.com/datasets/anshika2301/hr-analytics-dataset)
  (Used for educational purposes only)

⚠️ This project was developed for learning purposes by following an online tutorial and using open-source data. All visualizations, dashboard logic, and design implementations were created by me.

---

## 📫 Author

**Vaibhav Sharma**  

