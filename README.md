# COVID-19 Data Analysis Project

This Jupyter Notebook project explores the spread and impact of COVID-19 using real-world data from Our World in Data.

## 🎯 Objectives

- Load and explore global COVID-19 data
- Clean and preprocess the dataset
- Visualize trends in cases, deaths, and vaccinations
- Calculate and display death rates and vaccination coverage
- Communicate insights using graphs and clear commentary

## 🧰 Tools & Libraries Used

- Python 3
- Jupyter Notebook
- pandas
- matplotlib
- seaborn (optional)
- Git/GitHub

## 📊 Visualizations Included

- Total COVID-19 cases over time (line chart)
- Daily new cases per country
- Total deaths by country
- Death rate trends
- Bar chart for the most recent total cases

## 🗂️ Dataset

- Source: [Our World in Data COVID-19 dataset](https://ourworldindata.org/covid-cases)
- File: `owid-covid-data.csv` *(⚠️ Note: this file is large — 98MB)*

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Nedcarol/PYTHON-Assignment-8.git
   cd PYTHON-Assignment-8
---

### ✅ 2. **Reduce CSV File Size (Optional)**

#### Option 1: Filter only 3 countries (Kenya, India, USA) and export a smaller CSV
In Jupyter, run this:

```python
# Filter data
filtered_data = df[df['location'].isin(['Kenya', 'India', 'United States'])]

# Export to smaller CSV
filtered_data.to_csv('covid-small.csv', index=False)
