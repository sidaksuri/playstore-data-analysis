# 📱 Google Play Store Data Analysis

---

# 📌 Project Objectives

The primary objectives of this project are to:

- Clean and preprocess raw Google Play Store data.
- Handle missing values and inconsistent data types.
- Perform Exploratory Data Analysis (EDA).
- Create meaningful visualizations.
- Discover business insights from app-related data.

---

# 📂 Project Structure

```text
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
└── .gitignore
```

---

# 📊 Dataset

The dataset contains detailed information about Android applications available on the Google Play Store.

### Features

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type (Free/Paid)
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

---

# 🛠️ Tech Stack

- Python 3.13+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/sidaksuri/playstore-data-analysis.git
cd playstore-data-analysis
```

## Create a Virtual Environment

```bash
python -m venv .venv
```

### Activate the Environment

#### Windows (PowerShell)

```powershell
.\.venv\Scripts\Activate.ps1
```

#### Windows (Command Prompt)

```cmd
.venv\Scripts\activate.bat
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

# ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
GooglePlaystore-analysis.ipynb
```

Run the notebook cells sequentially.

---

# 📋 Workflow

### 1. Data Collection

- Load dataset
- Inspect rows and columns
- Understand feature types

### 2. Data Cleaning

- Handle missing values
- Remove duplicates
- Convert data types
- Clean Reviews, Size, Installs, and Price columns
- Format date columns
- Create derived features

### 3. Exploratory Data Analysis

- Rating distribution
- Category analysis
- Most installed applications
- Free vs Paid apps
- Review analysis
- Price analysis
- Size distribution
- Correlation analysis

### 4. Data Visualization

The project includes various visualizations such as:

- Count Plots
- Bar Charts
- Histograms
- Box Plots
- Scatter Plots
- Pie Charts
- Correlation Heatmaps

---

# 📈 Key Insights

- 📌 **Family** is the most popular app category.
- 🎮 **Games** receive the highest number of installs.
- 💰 The majority of applications are **free**.
- ⭐ Most app ratings lie between **4.0 and 4.5**.
- 📊 Apps with higher reviews generally have higher installs.
- 📱 Only a small percentage of apps are paid.

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

# 📄 pyproject.toml Support

This project also supports dependency management using **pyproject.toml**.

Install dependencies using:

```bash
pip install .
```

or

```bash
pip install -e .
```

---

# 📸 Sample Visualizations

You can include screenshots here, for example:

```
images/
├── category_distribution.png
├── rating_distribution.png
├── installs_analysis.png
└── heatmap.png
```

Then display them:

```markdown
![Category Distribution](images/category_distribution.png)

![Heatmap](images/heatmap.png)
```

---

# 🎯 Learning Outcomes

This project helped in understanding:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- Business Insight Generation
- Pandas Data Manipulation
- Data Preprocessing Techniques

---

# 🚀 Future Enhancements

- Build an interactive Streamlit dashboard.
- Deploy the project online.
- Perform advanced statistical analysis.
- Develop Machine Learning models for app rating prediction.
- Generate automated EDA reports.

---

# 👨‍💻 Author

**Sidak Singh Suri**

---

# ⭐ Support

If you found this project helpful, please consider **starring ⭐ the repository** and sharing your feedback.