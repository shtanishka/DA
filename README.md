# 📊 VCIS Internship Data Analysis Dashboard (2024)

This Power BI dashboard visualizes insights from the VCIS GD Schedules 2024 dataset, focusing on the distribution of selected candidates across colleges and academic programs.

## 🎯 Objectives

* Identify top 5 colleges and 5 programs (UG/PG) with the highest number of selections.
* Analyze course distribution across various colleges.
* Present the data through a clean, interactive Power BI dashboard.

## 🧾 Dataset Features

The dataset includes:

* Student Name
* College Name
* Course/Program Name

## 🧹 Data Cleaning

* Data was preprocessed using Python in Jupyter Notebook.
* Steps included:

  * Removing missing values
  * Standardizing college and course names
  * Formatting for Power BI compatibility

The cleaned dataset was then imported into Power BI for visualization.

## 📊 Dashboard Highlights

* **Top 5 Colleges** by selection count (Pie Chart)
* **Top 5 UG/PG Programs** (Bar Chart)
* **College-wise Course Distribution** (Matrix)
* **Summary Cards**: Total Students, Colleges, Courses
* Interactive Slicers for College and Program filtering

## 🛠 Tools Used

* Jupyter Notebook (Python - pandas, numpy)
* Power BI Desktop
* Excel

## 📁 Files Included

* `Dashboard.pbix` – Interactive Power BI dashboard file
* `Dashboard.pdf` – Static exported snapshot of the report
* `vcis_cleaning.ipynb` – Jupyter Notebook used for data cleaning
* `vcis data.xl` – excel file


## 🚀 How to Use

1. Clone or download the repository.
2. Open `Dashboard.pbix` in Power BI Desktop to explore visuals.
3. Run the Jupyter notebook (`vcis_cleaning.ipynb`) to view data cleaning steps.
4. Use `Dashboard.pdf` for quick reference or sharing.

## 📌 Insights

This project helps highlight which colleges and programs stand out in the VCIS selection process and allows for strategic analysis based on real selection data.

