## 📄 Project Overview

This project presents an exploratory and statistical analysis of a dataset containing information about Bollywood movies released between 2013 and 2015. The dataset includes variables related to box office performance and social media promotions. The analysis aims to identify key patterns, insights, and possible predictive relationships within the data.

---

## 📁 Repository Structure

* Jupyter notebook with the full data analysis workflow.
* `README.md`: Project overview and instructions.
* `bollywood.csv` dataset shared separately.

---

## 🧠 Key Objectives

1. Load and inspect the Bollywood movie dataset.
2. Clean the data, handle missing and duplicate values.
3. Perform exploratory data analysis (EDA).
4. Derive actionable insights from trends in the data.
5. Apply basic statistical modeling where applicable.

---

## 📊 Summary of Analysis and Insights

### Dataset Description

The dataset `bollywood.csv` includes:

* Movie names, genres, and star cast information.
* Box office collections (Opening, Weekend, and Lifetime Gross).
* Social media promotion metrics (YouTube Likes/Dislikes, Twitter data, etc.).

### Data Preparation Steps

* Handled missing values by imputing zeroes where appropriate (e.g., missing YouTube dislikes).
* Removed duplicate records.
* Checked for null values and ensured dataset integrity before analysis.

### Key Insights

* **Insight #1**: Movies with higher YouTube likes generally had better lifetime collections, suggesting that social media buzz correlates with success.
* **Insight #2**: Action and drama genres dominated both in number and average revenue generated.
* **Insight #3**: There is a positive correlation between opening week collections and lifetime collections, indicating that initial performance is a strong predictor of overall success.
* **Insight #4**: Movies with well-known star casts tend to receive more engagement on social media, but this does not always translate to box office success.
* **Insight #5**: Some movies with low YouTube dislikes and high likes underperformed, indicating that social media metrics alone are not foolproof indicators of success.

---

## ⚙️ Requirements

To run this notebook, install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🧪 How to Run

1. Clone this repository or download the files.
2. Ensure that the dataset `bollywood.csv` is placed in the working directory (or update the path in the notebook).
3. Open and run the notebook using JupyterLab, Jupyter Notebook, or Google Colab.

---

