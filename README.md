# Titanic Data Analysis & EDA

This repository contains an Exploratory Data Analysis (EDA) of the famous Titanic dataset. The goal is to investigate the factors that influenced the survival of passengers on the RMS Titanic.

## 🛳️ Project Overview

The project currently focuses on understanding the structure of the Titanic dataset, identifying missing values, and performing initial statistical summaries to gain insights into the demographics and survival rates of the passengers.

## 📂 Project Structure

- `data.csv`: The primary dataset containing passenger information.
- `eda.ipynb`: A Jupyter Notebook containing the data exploration and visualizations.
- `requirements.txt`: List of dependencies required to run the project.

## 🚀 Getting Started

Follow these steps to set up the project locally:

### 1. Create a Virtual Environment
It is recommended to use a virtual environment to keep dependencies isolated.
```bash
python -m venv venv
```

### 2. Activate the Virtual Environment
- **Windows**:
  ```bash
  venv\Scripts\activate
  ```
- **macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### 3. Install Dependencies
Install the required libraries using the provided `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### 4. Running the Analysis
Once the dependencies are installed, you can launch Jupyter Notebook to explore the analysis:
```bash
jupyter notebook
```
Then, open `eda.ipynb` from the Jupyter interface.

## 📊 Dataset Description

The `data.csv` file includes the following columns:

| Column | Description |
| :--- | :--- |
| **PassengerId** | Unique ID for each passenger |
| **Survived** | Survival (0 = No, 1 = Yes) |
| **Pclass** | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| **Name** | Name of the passenger |
| **Sex** | Gender |
| **Age** | Age in years |
| **SibSp** | # of siblings / spouses aboard the Titanic |
| **Parch** | # of parents / children aboard the Titanic |
| **Ticket** | Ticket number |
| **Fare** | Passenger fare |
| **Cabin** | Cabin number |
| **Embarked** | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

## 🛠️ Tools Used

- **Python**: Core programming language.
- **Pandas & NumPy**: For data manipulation and numerical analysis.
- **Matplotlib & Seaborn**: For creating insightful data visualizations.
- **Scikit-learn**: For machine learning and predictive modeling.
- **Jupyter Notebook**: For interactive data exploration.

---
*Developed as part of an AI & ML learning journey.*
