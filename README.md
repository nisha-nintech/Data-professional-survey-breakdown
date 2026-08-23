# 📊 Data Professional Survey Breakdown

## 📌 Project Overview

The **Data Professional Survey Breakdown** is an interactive **Power BI dashboard** created to analyze survey responses from professionals working in the data industry.

The project explores factors such as **salary, job titles, programming languages, job satisfaction, work-life balance, gender, age, and career preferences** to identify patterns and trends among data professionals.

The main goal of this project is to transform raw survey data into meaningful insights using **Power Query, data transformation, DAX, data modeling, and interactive data visualization**.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze the demographic profile of survey respondents.
- Understand salary patterns across different data-related job roles.
- Compare salaries across genders and job titles.
- Identify the most popular programming languages among data professionals.
- Analyze job satisfaction and work-life balance.
- Understand how respondents rate different aspects of their jobs.
- Build an interactive Power BI dashboard for exploring the survey data.
- Demonstrate practical skills in Power BI, DAX, Power Query, and data analysis.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Power BI** | Dashboard development and data visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Creating calculated measures and KPIs |
| **Excel / CSV** | Source dataset |
| **GitHub** | Project version control and documentation |

---

## 📂 Dataset

The dataset contains survey responses from professionals working in the data industry.

The dataset includes information related to:

- Age
- Gender
- Job Title
- Salary
- Programming Language
- Country
- Job Satisfaction
- Work-Life Balance
- Salary Satisfaction
- Professional background
- Other career-related information

---

## 🔄 Project Workflow

The project follows a typical data analytics workflow.

### 1. Data Collection

The survey dataset was imported into Power BI for analysis.

### 2. Data Cleaning

**Power Query** was used to prepare the dataset by:

- Removing unnecessary columns
- Handling missing values
- Correcting data types
- Cleaning inconsistent responses
- Transforming categorical data
- Preparing fields for analysis

### 3. Data Transformation

The cleaned dataset was transformed into a structured format suitable for analysis and visualization.

### 4. Data Modeling

The Power BI data model was prepared to support interactive analysis and dynamic filtering.

### 5. DAX Measures

Explicit DAX measures were created for important calculations and KPIs.

Example:

```DAX
Avg Salary Measure =
AVERAGE('Data Professional Survey'[Average Salary])
