# 💻 Stack Overflow Survey 2025 — Developer Market Analysis (EDA)

This project provides an exploratory data analysis (EDA) of the **Stack Overflow Developer Survey 2025** using Python.  
The goal is to identify key trends in the global developer market and translate raw survey data into clear, business-relevant insights.

The analysis serves as the analytical foundation for a professional **Tableau dashboard**.

---

## 🖥️ Dashboard Preview

<p align="center">
  <img src="assets/Dashboard — Market Overview.png" alt="Dashboard Preview" width="850">
</p>

---

## ⭐ Project Highlights

- End-to-end EDA workflow: data inspection → validation → analysis → insights  
- Analysis of **real-world developer market trends** based on a large-scale global survey  
- Focus areas:
  - remote vs hybrid work models  
  - Python adoption  
  - learning paths into programming  
  - compensation by geography and industry  
- Clear, business-oriented interpretation of results  
- Clean and structured Jupyter Notebook suitable for a professional portfolio  
- **Interactive Tableau Public dashboard** built on top of the analysis  

---

## 📊 Interactive Dashboard (Tableau Public)

This project includes an interactive BI dashboard built in **Tableau Public**.  
It allows exploration of developer market trends using filters such as:

- Country  
- Age group  
- Industry  
- Work format (remote / hybrid / on-site)  

Contains:
- KPI overview cards  
- Python adoption metrics  
- Compensation distribution by geography  
- Industry breakdown of high-paid remote developers  

🔗 **Dashboard link:**  
👉 *https://public.tableau.com/views/StackOverflowSurvey2025DeveloperMarketAnalysis/DashboardMarketOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link*

> Note: The dashboard is based on a filtered subset of respondents with valid annual compensation values.  
> As a result, total counts may differ from the full survey sample used in exploratory analysis.

---

## 📂 Repository Structure
```
stack-overflow-survey-2025-analysis/
│
├── notebook/
│ └── stack_overflow_survey_2025_analysis.ipynb
│
├── data/
│ └── (CSV files downloaded separately)
│
├── assets/
│ └── dashboard_screenshot.png
│
├── README.md
├── requirements.txt
└── .gitignore
```
---

## 🔧 Technologies Used

- Python 3  
- pandas  
- Jupyter Notebook  
- Tableau Public (interactive dashboard)

> Only essential libraries are used to keep the project lightweight and easy to reproduce.

---

## 📊 Key Insights

- **Remote work:** fully remote developers represent a minority, indicating continued dominance of hybrid and on-site models  
- **Python popularity:** Python is widely adopted across all age groups, with the highest adoption among younger developers (18–24)  
- **Learning paths:** online courses are one of the most common ways to enter programming, highlighting the importance of alternative education  
- **Compensation:** annual pay varies significantly by geography and industry  
- **Top-paid developers:** no single education level dominates among the highest earners  
- **High-paid remote roles:** most are concentrated in Software Development, with strong representation in FinTech and tech-driven Healthcare  

---

## 🚀 How to Run the Project Locally

### 1. Clone the repository

```bash
git clone <repo-url>
cd stack-overflow-survey-2025-analysis
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Download the dataset
This project uses the Stack Overflow Developer Survey 2025 public dataset.
Download the following files from Stack Overflow:

**survey_results_public.csv**

**survey_results_schema.csv**

Place them into the data/ folder:
```
data/
├── survey_results_public.csv
└── survey_results_schema.csv
```
### 4. Run the analysis
Start Jupyter Notebook from the project root:
```bash
jupyter notebook
```
Then open the notebook:
```
notebook/stack_overflow_survey_2025_analysis.ipynb
```
Restart the kernel and run all cells to reproduce the analysis.

---

## 📎 Data Source
Stack Overflow Developer Survey 2025

Public survey data provided by Stack Overflow

---

## ✨ Final Notes
This project demonstrates a structured, end-to-end analytical approach:
from raw survey data to actionable insights and BI visualization.

It is designed as a portfolio-ready data analytics case study, emphasizing clarity, reproducibility, and real-world relevance.

---

## 📌 License

This project is for educational and portfolio purposes only.

