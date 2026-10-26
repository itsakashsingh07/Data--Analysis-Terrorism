# 🌍 Global Terrorism Analysis | Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on analyzing global terrorism incidents using **Exploratory Data Analysis (EDA)** in Python. The objective is to identify patterns and trends in terrorist activities across different countries, regions, years, attack types, weapons, and target categories.

The analysis uses data cleaning, statistical exploration, and data visualization to understand the distribution of terrorism incidents and identify regions and categories with high incident counts.

## 🎯 Objectives

- Analyze the yearly distribution of terrorism incidents and identify historical trends.
- Identify the countries, regions, states, and cities with the highest numbers of recorded incidents.
- Examine the most common attack types and weapons used.
- Understand the distribution of incidents across different target categories.
- Explore monthly and daily patterns in recorded incidents.
- Present findings through visualizations using Python.

## 🛠️ Tech Stack

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots and visualizations |
| Jupyter Notebook | Interactive analysis |

## 📂 Project Structure

```text
Global-Terrorism-Analysis/
│
├── Terrorism_EDA.ipynb
├── Terrorism_dataset.csv
└── README.md
```

**Note:** The CSV file is required to run the notebook. Include it in the repository only if its licensing and distribution terms permit; otherwise, provide instructions for obtaining it.

## 📊 Dataset Description

The notebook works with a terrorism dataset containing **181,691 records and 135 columns** before preprocessing.

For analysis, the project selects 12 relevant columns:

- `Year` – Year of the incident
- `Month` – Month of the incident
- `Day` – Day of the incident
- `Country` – Country where the incident occurred
- `Region` – Geographic region
- `State` – State or province
- `City` – City of the incident
- `Attack_type` – Type of attack
- `Target_type` – Category of the target
- `Target_subtype` – Specific target category
- `Gang_name` – Group associated with the incident
- `Weapon_type` – Weapon category used

The selected dataset retains all **181,691 records** while reducing the number of columns from 135 to 12.

## ⚙️ Project Workflow

### 1. Data Loading and Exploration
- Imported the dataset using Pandas.
- Examined the dataset dimensions, column names, data types, and summary statistics.
- Identified unique countries and groups represented in the dataset.

### 2. Data Cleaning and Preprocessing
- Renamed selected columns for improved readability.
- Selected 12 columns relevant to the analysis.
- Replaced missing target-subtype values with `Others`.
- Replaced missing state and city values with `Unknown`.
- Standardized selected attack-related category labels.
- Checked for missing values after preprocessing.

### 3. Exploratory Data Analysis
Analyzed incident counts across multiple dimensions:

- Top 10 countries by recorded incident count
- Top 10 regions and states
- Top 10 cities
- Most frequent attack types
- Most frequently targeted categories
- Groups associated with the highest incident counts
- Most frequently recorded weapon categories

### 4. Data Visualization
Used Matplotlib and Seaborn to create count plots for:

- Attacks by year
- Attacks by month
- Attacks by day
- Attacks by country
- Attacks by region
- Attacks by target type
- Attacks by attack type
- Distribution of weapon categories

These visualizations help identify prominent categories and historical patterns in the recorded data.



- **Attack types:** Explosions and bombings represent a prominent attack category, followed by other methods such as firearms.
- **Yearly trends:** Recorded incidents peaked around 2014, with a decline visible in
