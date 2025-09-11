# 🚢 Titanic Survival Predictions  

**A Jupyter Notebook project that analyzes the Titanic dataset to explore patterns in passenger survival.**  
This repository contains an exploratory analysis pipeline with data cleaning, feature engineering, and visualizations that prepare the dataset for modeling.  

## 📌 What this project does  
- 📂 Loads the Titanic dataset (`Titanic-Dataset.csv`) and inspects data quality.  
- 🛠 Cleans and engineers features (e.g., `HasCabin`, `Title`, `Age` imputation).  
- 📊 Produces visualizations that reveal survival patterns by sex, class, family size, and age.  
- 📑 Prints grouped survival percentages for quick interpretation.  

## 📁 Files in this repo  
- `titanic-survival-predictions.ipynb` — the main notebook.  
- `Titanic-Dataset.csv` — dataset used inside the notebook.  
- `README.md` — this file.  

## 🖥 Tools & technologies  
- 🐍 Python (3.14)  
- 📓 Jupyter Notebook  
- 📦 Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`  

## ⚙️ How to run  
1. Clone the repository.  
2. Install the required libraries (`numpy`, `pandas`, `matplotlib`, `seaborn`, `jupyter`).  
3. Open and run the notebook with Jupyter.  

## 🔎 Workflow  
1. Import libraries.  
2. Load and explore the dataset.  
3. Analyze data types and missing values.  
4. Clean and engineer features (`HasCabin`, `Title`, `AgeGroup`).  
5. Visualize survival patterns by different variables.  
6. Summarize key findings.  

## 📊 Key findings  
- 👩‍🦰 **Sex**: Females had a much higher survival rate than males.  
- 🛳 **Pclass**: 1st class passengers survived more often than 2nd and 3rd class.  
- 👶 **Age**: Babies and young children were more likely to survive.  
- 👨‍👩‍👧 **Family**: Moderate family size (1–2 relatives) improved survival chances.  
- 🏠 **Cabin presence**: Passengers with a recorded cabin had higher survival.  

## 📜 License  
This project uses the **MIT License** — feel free to use, modify, and share.  
