# tableau_ibm_anylasis
<p align="center">
  <img src="assets/IBM_logo.png" alt="IBM Logo" width="200"/>
</p>

# IBM HR Employee Attrition Analysis (Tableau)

An interactive Tableau workbook analyzing the IBM HR Analytics Employee Attrition dataset — exploring workforce demographics, compensation, tenure, and attrition patterns across departments and job roles.

## 📊 Worksheets included

- Average Age
- Avg Age by Department and Job Role
- Avg Monthly Income by Department and Job Role
- Avg Total Working Years
- Avg Years at Company
- Gender and Job Roles
- Gender Distribution in the Company
- Total Employees by Education Field
- Total Employees
- Total Employees by Department and Job Role
- Gender and Marital Status
- Number of Companies Worked For

## 🗂️ Dataset

Built on the **IBM HR Analytics Employee Attrition & Performance** dataset (`WA_Fn-UseC_-HR-Employee-Attrition.csv`), a widely used fictional HR dataset with 1,470 employee records and 35 attributes, including:

- Demographics: `Age`, `Gender`, `MaritalStatus`, `EducationField`
- Job details: `Department`, `JobRole`, `JobLevel`, `BusinessTravel`
- Compensation: `MonthlyIncome`, `DailyRate`, `PercentSalaryHike`, `StockOptionLevel`
- Tenure & satisfaction: `YearsAtCompany`, `TotalWorkingYears`, `JobSatisfaction`, `WorkLifeBalance`, `Attrition`

> The dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset). It is not bundled in this repo — download it separately and place it in a `data/` folder to reconnect the workbook (see below).

## 📁 Project structure

```
ibm-hr-attrition-tableau/
├── assets/
│   └── IBM_logo.png
├── ibm_hr_attrition.twb
└── README.md
```

## 🚀 Getting started

1. Download the dataset CSV from Kaggle (link above) and place it in a `data/` folder in the project root.
2. Open `ibm_hr_attrition.twb` in [Tableau Desktop](https://www.tableau.com/products/desktop) (or Tableau Public/Reader).
3. If prompted, reconnect the data source to point to your local `data/WA_Fn-UseC_-HR-Employee-Attrition.csv`.

## 🛠️ Tech stack

- Tableau Desktop (workbook version 18.1 / 2026.2)
- IBM HR Analytics dataset (CSV)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
