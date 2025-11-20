

# **COVID-19 Global Data Tracker**

A data analysis project exploring COVID-19 cases, deaths, and vaccination progress across **Australia, Egypt, and England**, using the *Our World in Data* COVID-19 dataset. The goal is to compare pandemic impacts, identify trends, and analyze differences in mortality and vaccination rollout.

---

## ⭐ Executive Summary

This project analyzes COVID-19 trends from 2020–2023, focusing on three countries with diverse healthcare systems and reporting quality. The analysis highlights **case growth**, **death rates**, and **vaccination progress**, revealing strong regional disparities and data completeness issues.

---

## 🎯 Objectives

* Analyze trends in **total cases**, **deaths**, and **vaccinations**
* Compute and compare **death rates**
* Visualize case and vaccination growth
* Identify regional disparities and data gaps
* Derive insights from publicly available COVID-19 data

---

## 📘 Dataset

**Source:** Our World In Data (OWID)
[https://docs.owid.io/projects/covid/en/latest/dataset.html](https://docs.owid.io/projects/covid/en/latest/dataset.html)

**File Used:** `owid-covid-data.csv`
**Columns:** 67 features including total cases, deaths, vaccinations, population, and healthcare indicators.

---

## 🛠 Tools & Technologies

* Python
* Pandas
* Matplotlib & Seaborn
* Jupyter Notebook
* GitHub

---

## 📌 Methodology

1. Imported and explored the OWID COVID-19 dataset
2. Filtered data for **Australia**, **Egypt**, and **England**
3. Cleaned missing values in selected fields
4. Calculated additional metrics (e.g., *death rate*)
5. Created visualizations for case and vaccination analysis
6. Summarized findings and limitations

---

## 📊 Visualizations

*(Generated in the notebook — add images in your repo for better presentation)*

* Total COVID-19 cases over time
* Vaccination rollout comparison
* Death rate calculations

---

## 🔍 Key Insights

### 📈 Case Trends

* **Australia** shows exponential growth (≈11.8M cases peak).
* **Egypt** shows steady but moderate growth.
* **England** has limited data due to OWID’s reporting structure.

### ⚰️ Death Rates

* **Egypt:** ~5.05% (highest)
* **Australia:** ~1.05%
* **England:** Missing data (NaN)

### 💉 Vaccination Progress

* England has the highest total vaccinations.
* Population size affects the dose distribution.
* Africa’s region shows significant data availability gaps.

---

## ⚠️ Data Limitations

* Missing values in early pandemic dates
* England’s dataset is incomplete
* Dataset lacks many major countries
* Replacing missing values with zero reduces accuracy

---

## 🧭 Next Steps / Improvements

* Add more regions (Kenya, South Africa, USA)
* Build an interactive dashboard (Power BI, Streamlit)
* Forecast cases using machine learning
* Improve missing value handling (e.g., interpolation)

---

## ▶️ How to Run the Project

**1. Clone the repo**

```bash
git clone https://github.com/codewith-samuel/COVID-19-Global-Data-Tracker-Project
cd COVID-19-Global-Data-Tracker-Project
```


**2. Download and place the dataset**
Download `owid-covid-data.csv` from OWID and place it in the `data/` folder.

**3. Run the notebook**

```bash
jupyter notebook
```

---

## 📂 Project Structure

```
COVID-19-Global-Data-Tracker-Project/
│
├── data/
│   └── owid-covid-data.csv
├── notebooks/
│   └── COVID-19-Global-Data-Tracker-Project.ipynb
├── visuals/
│   ├── total_cases_plot.png
│   └── vaccinations_plot.png
├── README.md
└── requirements.txt
```

---

## 👤 Author

**Samuel Waithaka**
📍 Nairobi, Kenya
🔗 LinkedIn: [https://www.linkedin.com/in/samuel-waithaka-03753928b](https://www.linkedin.com/in/samuel-waithaka-03753928b)
📧 Email: [waithakas2003@gmail.com](mailto:waithakas2003@gmail.com)
🐙 GitHub: [https://github.com/codewith-samuel](https://github.com/codewith-samuel)

