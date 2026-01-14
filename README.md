# 🧮 Statistics Toolkit: Comprehensive Web Calculator

> A comprehensive, full-featured web application providing an intuitive interface for performing various advanced statistical calculations, powered by Flask and dedicated statistics modules.

<p align="center">
  <img src="https://img.shields.io/badge/Framework-Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Framework: Flask" />
  <img src="https://img.shields.io/badge/Persistence-SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="Persistence: SQLite" />
</p>

## 🎯 Key Capabilities

| Calculation Type | Description | Included Tools |
| :---: | :--- | :--- |
| **Fundamental** | Calculates basic measures for data summarization. | Mean, Median, Mode, Range, Variance, Standard Deviation, Quartiles, Outlier Identification. |
| **Hypothesis Testing** | Compares means and variances across multiple groups. | **ANOVA** (Analysis of Variance). |
| **Modeling** | Determines linear relationships between variables. | **Simple Linear Regression** Analysis. |
| **Probability** | Calculates probabilities for continuous data sets. | **Normal Distribution** (Z-Scores, P-Values). |
| **Inference** | Estimates population parameters with a degree of certainty. | Various **Confidence Intervals** (e.g., Mean, Proportion). |

## 🛠️ User Features

* **Calculation History**: Automatically saves all results for later review and revisits.
* **Sample Datasets**: Access pre-loaded, categorized datasets for quick testing and demonstration.
* **Intuitive Interface**: Easy navigation via a top menu and clear dropdowns to access specific statistical tools.

## 💻 Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) |
| **Framework** | ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) |
| **Database** | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) |
| **Frontend** | HTML, CSS, Jinja Templating |
| **Requirements** | Python 3.8+ |


## Project Structure

```
statistics-toolkit/
├── blueprints/             # 🧩 Route definitions (descriptive.py, linear.py, etc.)
├── statisticss/            # 🧮 Core statistical calculation functions
├── templates/              # 🎨 HTML templates and views
├── static/                 # 🖼️ CSS and assets (screenshot.png)
├── dataset/                # 💾 Sample datasets and initialisation script
├── requirements.txt
└── app.py                  # Main entry point
```
  
## ⚙️ Installation & Run

### 1. Setup

```bash
# Clone the repository
git clone https://github.com/peiyan0/python-statistic-app.git
cd python-statistic-app
```
### 2. Environment Setup

```bash
# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```
### 3. Database Initialization

```bash
# Populate the SQLite database with sample datasets
cd dataset
python script.py
cd .. # Move back to the root directory
```
### 4. Run Application

```bash
# Start the Flask development server
flask run

# Access the application in your browser
http://localhost:5000
```

![App Screenshot](static/screenshot.png)
