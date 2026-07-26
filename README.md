# 📱 Google Play Store Data Analysis

A complete Exploratory Data Analysis (EDA) project on the Google Play Store dataset using Python. This project focuses on understanding app categories, ratings, reviews, installs, pricing, and other important features through data cleaning, preprocessing, and visualization.

---

## 📌 Project Overview

The objective of this project is to:

- Clean and preprocess the Google Play Store dataset.
- Handle missing values and incorrect data types.
- Perform Exploratory Data Analysis (EDA).
- Visualize trends and patterns.
- Extract meaningful business insights.

---

## 📂 Project Structure

```
playstore-data-analysis/
│
├── data/
│   ├── googleplaystore.csv
│   └── google_cleaned.csv
│
├── GooglePlaystore-analysis.ipynb
├── requirements.txt
├── pyproject.toml
├── README.md
└── .venv/
```

---

## 📊 Dataset

Dataset: **Google Play Store Apps**

Features include:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Android Version

---

## 🛠️ Technologies Used

- Python 3.13+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📦 Installation

### Clone the repository

```bash
git clone <repository-url>
cd playstore-data-analysis
```

### Create Virtual Environment

Windows

```bash
python -m venv .venv
```

Activate

PowerShell

```powershell
.\.venv\Scripts\Activate.ps1
```

Command Prompt

```cmd
.venv\Scripts\activate.bat
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Run the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
GooglePlaystore-analysis.ipynb
```

and execute the cells sequentially.

---

## 📋 Project Workflow

### 1. Data Loading

- Import dataset
- Inspect shape
- View columns
- Check data types

### 2. Data Cleaning

- Remove duplicate records
- Handle missing values
- Convert numerical columns
- Clean Size, Reviews, Installs and Price columns
- Convert Date columns
- Create new derived features

### 3. Exploratory Data Analysis

- Distribution of Ratings
- Category-wise analysis
- Most Installed Apps
- Free vs Paid Apps
- Rating Distribution
- Price Distribution
- Reviews Analysis
- Size Analysis
- Correlation Heatmap

### 4. Data Visualization

Visualizations created using:

- Count Plots
- Bar Charts
- Histograms
- Box Plots
- Scatter Plots
- Pie Charts
- Heatmaps

---

## 📈 Insights

Some of the insights obtained include:

- Most apps belong to the **Family** category.
- Free apps dominate the Play Store.
- Games receive significantly higher installs.
- Most apps are priced at \$0.
- Ratings are concentrated between **4.0–4.5**.
- A small number of apps account for the majority of downloads.
- Higher review counts generally indicate higher installs.

---

## 📦 Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 📄 pyproject.toml

This project also supports dependency management using **pyproject.toml**.

Install dependencies with:

```bash
pip install .
```

or

```bash
pip install -e .
```

---

## 📚 Learning Outcomes

Through this project you will learn:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- Business Insight Generation
- Working with Pandas
- Data Preprocessing Techniques

---

## 🚀 Future Improvements

- Build an interactive Streamlit dashboard.
- Perform advanced statistical analysis.
- Develop machine learning models for rating prediction.
- Create automated EDA reports.
- Deploy the project as a web application.

---

## 👨‍💻 Author

**Sidak Singh Suri**

---

## ⭐ If you found this project useful, consider giving it a star!