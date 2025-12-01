# Mental Health Survey – Exploratory Data Analysis (EDA)

This project analyzes a mental health survey with 1,245 responses to explore treatment-seeking behavior across demographic and workplace factors. The goal is to understand patterns, clean the dataset using multiple tools, and visualize the results through dashboards and Python charts.

This project demonstrates a full end-to-end EDA workflow using:

- **Excel** (data cleaning & pivot tables)  
- **Tableau** (interactive dashboards)  
- **Python + Pandas** (data cleaning & inspection)  
- **Python + Seaborn** (statistical visualizations)  
- **Python + Matplotlib** (manual, low-level chart creation)  
---
## Project Files
```
mental_health_project/
│
├── mental_health_survey2.csv # Original dataset
├── mental_health_clean_excel_.xlsx # Cleaned Excel dataset
│
├── Visualized_with_Excel_mental_health.pdf # Excel analysis
├── Visualized_with_Tableau_mental_health.pdf # Tableau dashboard
├── Visualized_with_Seaborn_mental_health.pdf # Python Seaborn visualizations
├── Visualized_with_Matplotlib_mental_health.pdf # Python Matplotlib visualizations
│
├── treatment_overall.png
├── treatment_by_gender_group.png
├── treatment_by_company_size.png
├── treatment_overall_matplotlib.png
├── treatment_by_gender_matplotlib.png
│
└── README.md
```
---

## Dataset Overview

The dataset includes 1,245 survey responses with fields such as:

- Age  
- Gender  
- Country  
- Work conditions  
- Mental health treatment history  
- Company size  
- Support systems at work  
- Perceived consequences of seeking help  

After cleaning, we standardized:

- **Age:** removed outliers, created clean age groups  
- **Gender:** grouped into `male`, `female`, `nonbinary`, `other`, `queer`  
- **Company size:** cleaned and normalized (`no_employees_clean`)  

---

# 1️ Excel Analysis  

Excel was used to:

- Clean the dataset  
- Create helper columns (`Age_clean`, `Age_group`, `Gender_group`, `no_employees_clean`)  
- Build PivotTables  
- Produce basic bar charts  
- Export a PDF summary report  

This demonstrates traditional business-friendly cleaning and analysis workflows.

---

# 2️ Tableau Dashboard  

A Tableau dashboard was created with:

- Treatment by Gender  
- Treatment by Age Group  
- Treatment by Company Size  

The dashboard supports dynamic exploration and clear storytelling.  

---

# 3️ Python + Seaborn Visualizations  

Seaborn was used to generate fast, clean, statistical visualizations.

### Key Charts (Seaborn)

- Overall Treatment Count  
- Treatment by Gender Group  
- Treatment by Age Group  
- Treatment by Company Size  

### Seaborn Insights

**Overall Treatment Count**  
A nearly even split between respondents who have and have not sought treatment.

**Treatment by Gender**  
Female respondents show higher treatment-seeking behavior. Males participate more in total, but proportionally seek treatment less.

**Treatment by Age Group**  
Most respondents fall in the 25–34 age group, which also has the highest number of “Yes” responses.

**Treatment by Company Size**  
Mid-sized companies (26–100 and 100–500 employees) show the highest treatment-seeking rates.

---

# 4️ Python + Matplotlib Visualizations  

Matplotlib charts were manually constructed to show full control of:

- Bar positions  
- Bar widths  
- Axis labels  
- Layout  

### Matplotlib Insights

**Overall Treatment Count**  
Manually replicates the distribution, emphasizing differences between low-level Matplotlib and high-level Seaborn.

**Treatment by Gender**  
Grouped bars replicate Seaborn’s trend: females proportionally seek treatment more than males. Smaller gender categories lean toward “Yes” despite small sample sizes.

---

##  Technical Skills Demonstrated

- Data cleaning (Excel & Pandas)  
- Data visualization (Tableau, Seaborn, Matplotlib)  
- Grouping, aggregation, and categorical analysis  
- Exploratory Data Analysis workflow  
- Documentation, storytelling, and GitHub project organization  

---

##  About the Author

I’m **Claudia G Atkins**, a bilingual engineer and project manager transitioning into data analytics. I combine operational leadership with analytical thinking, using Excel, Tableau, and Python to uncover insights and improve processes. With experience managing nationwide IT service desks, coordinating large-scale programs, and implementing quality standards, I am now focused on building data-driven solutions and visual dashboards that support strategic decision-making.

**Tools & Skills:**
- Python (Pandas, Seaborn, Matplotlib)  
- Excel (advanced cleaning, formulas, pivot tables)  
- Tableau (interactive dashboards)  

---

#  End of README

