# 🧠 Data Science Job Market Analysis (2020)

## 📌 Project Overview

This project analyzes the Data Science job market in India using data scraped from [Naukri.com](https://www.naukri.com/).  
It includes the following pipeline:

1. Web scraping of job postings using Selenium.
2. Data cleaning and preprocessing.
3. Exploratory Data Analysis (EDA) to uncover job market trends.

---

## Dependencies:
* Python
* matplotlib
* pandas
* selenium

## 🚀 Step-by-Step Instructions
Ensure you have Python 3.8+ installed.


### 🥽 Step 1: Set up the Virtual Environment
#### Option A: Using venv (recommended)

```bash
python -m venv ds_env
source ds_env/bin/activate    # On Windows: ds_env\Scripts\activate

pip install -r requirements.txt
```

#### Option B: Using conda

```bash
conda create -n ds_env python=3.8
conda activate ds_env
pip install -r requirements.txt
```

### 🌐 Step 2: Run the Scraper.ipynb
This will scrape job listings from Naukri.com.

#### Option A: Using VSCode (recommended)

See the [setup-guide](EnvSetupGuide.pdf) to activate enviroment in VSCode.

#### Option B: Using Jupyter Notebook Web Interface

```bash
# Run from terminal or Jupyter
jupyter notebook scraper.ipynb
```
See the [setup-guide](EnvSetupGuide.pdf) to activate enviroment in Jupyter.


This will scrape job listings from Naukri.com.

✅ Output: data_scientist_jobs.csv will be created with raw job listings.

### 🧹 Step 3: Clean the Data
Open and run the Job_market_analysis.ipynb notebook. This step involves:

- Removing duplicates

- Handling null values

- Formatting job roles and salary info

💾 Output: Cleaned dataset ready for analysis.

### 📊 Step 4: Perform EDA
Continue in the same notebook:

- Visualize common job titles, skills, locations, and companies.

- Analyze salary trends and required experience levels.

- Uses matplotlib for plotting insights.