# Titanic EDA – Exploratory Data Analysis

**Author:** Tirtha Dutta  
**Date:** 24 June 2025  
**Dataset:** [Kaggle – Yasser H Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

##  Objective

Explore the Titanic dataset using visual and statistical techniques to uncover relationships, trends, and anomalies.  
This step helps lay the foundation for building accurate machine learning models.

---

##  Key EDA Steps Performed

1. Summary statistics for all numerical features  
2. Histograms to visualize distributions  
3. Boxplots to inspect outliers and spread  
4. Correlation heatmap to check relationships  
5. Markdown cell summarizing key findings

---

##  Folder Structure

```text
titanic-eda/
├── data/
│   └── titanic_cleaned.csv               # Cleaned dataset (from Task 1)
│
├── images/
│   ├── histograms.png                    # Histograms of numeric features
│   ├── boxplots.png                      # Boxplots for outlier inspection
│   └── correlation_heatmap.png          # Correlation heatmap
│
├── notebooks/
│   ├── 01_eda_walkthrough.ipynb          # Jupyter notebook with all EDA steps
│   └── .ipynb_checkpoints/               # Jupyter autosave folder (ignored by Git)
│
├── requirements.txt                      # List of required Python packages
├── .gitignore                            # Fi


---

##  How to Run Locally

```bash
git clone https://github.com/tirtha103/titanic-eda.git
cd titanic-eda

# Create and activate virtual environment (Windows)
python -m venv venv
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter lab notebooks/01_eda_walkthrough.ipynb

