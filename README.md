# Unemployment Analysis 📊

This project is part of my **CodeAlpha Data Science Internship**.

In this project, I analyzed unemployment data from India to understand unemployment patterns across different regions, areas, and time periods.

## What I Did

- Loaded the unemployment dataset using Pandas
- Checked the dataset structure and data types
- Checked for missing values
- Removed duplicate records
- Cleaned column names
- Converted the Date column into datetime format
- Performed statistical analysis
- Calculated average unemployment rates
- Compared unemployment rates across regions
- Compared Urban and Rural unemployment
- Analyzed unemployment trends over time
- Analyzed estimated employment by region
- Studied the relationship between unemployment and labour participation
- Created visualizations using Matplotlib and Seaborn

## Dataset

The original dataset contained:

- **768 records**
- **7 columns**

After removing **27 duplicate records**, the dataset contained:

- **741 records**

Main columns:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preprocessing

The dataset was checked for missing values and duplicate records.

There were **27 duplicate records**, which were removed.

The column names were also cleaned by removing unnecessary leading and trailing spaces.

The `Date` column was converted into a proper datetime format for time-based analysis.

## Analysis Results

The overall average unemployment rate in the cleaned dataset was:

**11.79%**

### Average Unemployment by Area

- Rural: **10.32%**
- Urban: **13.17%**

### Regions with Higher Average Unemployment Rates

The analysis identified the following regions among the highest average unemployment rates:

- Tripura: **28.35%**
- Haryana: **26.28%**
- Jharkhand: **20.59%**
- Bihar: **18.92%**
- Himachal Pradesh: **18.54%**

### Regions with Lower Average Unemployment Rates

The analysis identified the following regions among the lower average unemployment rates:

- Meghalaya: **4.80%**
- Odisha: **5.66%**
- Assam: **6.43%**
- Uttarakhand: **6.58%**
- Gujarat: **6.66%**

## Visualizations

The project includes visualizations for:

1. Average unemployment rate by region
2. Urban vs Rural unemployment
3. Unemployment rate over time
4. Average estimated employment by region
5. Unemployment rate vs labour participation rate
6. Correlation heatmap

## Correlation Analysis

The Pearson correlation between:

- Estimated Unemployment Rate (%)
- Estimated Labour Participation Rate (%)

was approximately:

**0.003**

This indicates that there was very little linear correlation between these two variables in this dataset.

## Project Structure

```text
CodeAlpha_UnemploymentAnalysis/
│
├── Unemployment_Analysis.ipynb
├── Unemployment in India.csv
├── README.md
├── requirements.txt
└── .gitignore


How to Run

Clone the repository:
git clone YOUR_GITHUB_REPOSITORY_URL

Move into the project folder:
cd CodeAlpha_UnemploymentAnalysis

Create a virtual environment:
python3 -m venv .venv

Activate it:
source .venv/bin/activate


Install the required libraries:
pip install -r requirements.txt


Open:
Unemployment_Analysis.ipynb

Run the notebook cells from top to bottom.


What I Learned
Through this project, I gained practical experience in data cleaning, exploratory data analysis, statistical analysis, data visualization, time-series analysis, and correlation analysis using Python.

Internship
CodeAlpha Data Science Internship

Author
Sourav Kumar
