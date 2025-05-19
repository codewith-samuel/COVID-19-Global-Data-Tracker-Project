# COVID-19-Global-Data-Tracker-Project
COVID-19 Global Data Tracker
Description
This project analyzes COVID-19 data to track cases, deaths, and vaccination progress in Australia, Egypt, and England using the Our World in Data dataset. It provides visualizations and insights into pandemic trends, with a focus on death rates and vaccination rollouts, offering a comparative view across these regions.
Objectives

Analyze trends in total cases, deaths, and vaccinations over time for Australia, Egypt, and England.
Calculate and compare death rates to understand mortality impacts.
Visualize case growth and vaccination progress using line plots.
Identify regional disparities, particularly for Egypt in the African context.
Share findings through a public GitHub repository for broader accessibility.

Tools and Libraries

Python 3: Core programming language.
Jupyter Notebook: For interactive data analysis and visualization.
Pandas: Data manipulation and analysis.
Matplotlib & Seaborn: Plotting case and vaccination trends.
Dataset: owid-covid-data.csv from Our World in Data.
GitHub: Hosting the project repository.

How to Run/View the Project

Clone the Repository:git clone https://github.com/your-username/covid-19-data-tracker.git
cd covid-19-data-tracker


Install Dependencies:Install required Python libraries:pip install pandas matplotlib seaborn jupyter


Download the Dataset:
Download owid-covid-data.csv from Our World in Data.
Place it in the project folder or update the file path in the notebook.


Run the Notebook:
Start Jupyter Notebook:jupyter notebook


Open covid_tracker.ipynb and run all cells to reproduce the analysis and plots.


View Outputs:
Visualizations are saved as total_cases_plot.png and vaccinations_plot.png.
Key statistics (e.g., death rates) are displayed in the notebook outputs.


Alternative: View the notebook directly on GitHub or use nbviewer for rendered output by pasting the notebook’s GitHub URL.

Insights and Reflections

Case Trends: Australia exhibited exponential case growth, reaching ~11.86 million cases, driven by later waves (e.g., Omicron). Egypt showed moderate growth, while England’s lower case curve suggests potential data gaps, possibly due to its sub-regional classification.
Death Rates: Egypt’s high death rate (5.05%) highlights healthcare challenges in North Africa, contrasting with Australia’s low rate (1.05%), reflecting robust medical systems. England’s unavailable death rate (NaN) indicates missing case data, limiting comparisons.
Vaccination Progress: England led with 149.4 million doses, followed by Egypt and Australia, reflecting differences in population size and rollout speed. Australia’s trailing vaccination curve may be due to its smaller population (26M).
Data Challenges: Filling missing values with 0 may underestimate early cases/deaths. The dataset’s limited scope (missing Kenya, USA, India) suggests it’s a subset, reducing global context.
Reflections: Analyzing Egypt provided valuable African insights, but including more African countries (e.g., South Africa) would enhance relevance for East Africa. Working with Jupyter and GitHub improved my data analysis and sharing skills, though dataset limitations underscored the need for comprehensive sources.

