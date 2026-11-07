# Google-advanced-data-analytics-capstone
# Google-advanced-data-analytics-capstone: Salifort Motors Employee Retention Project

This repository contains the end-to-end capstone project for the Google Advanced Data Analytics Professional Certificate, focusing on exploratory data analysis, predictive modeling, machine learning classification, and business insights to address employee turnover at Salifort Motors.

---

## 📂 Repository Contents & File Breakdown

* **[`1--Activity Course 6 Salifort Motors project la.pdf`](https://github.com/dyyland23-glitch/Google-advanced-data-analytics-capstone/blob/main/1--Activity%20Course%206%20Salifort%20Motors%20project%20la.pdf)**: 
  * *What it is*: Comprehensive project documentation detailing the structured PACE (Plan, Analyze, Construct, Execute) framework methodology, feature engineering steps, model tuning results, and strategic HR recommendations.
* **[`HR_capstone_dataset.csv`](https://github.com/dyyland23-glitch/Google-advanced-data-analytics-capstone/blob/main/HR_capstone_dataset.csv)**: 
  * *What it is*: The primary dataset containing employee metrics including satisfaction levels, last evaluation scores, number of projects, average monthly hours, tenure, work accidents, promotions, department classifications, and the target turnover indicator (`left`).
* **[`README.md`](https://github.com/dyyland23-glitch/Google-advanced-data-analytics-capstone/blob/main/README.md)**: 
  * *What it is*: Project overview, repository structure, and execution instructions.

---

## 🎯 Project Overview & Key Methods

* **Project Objective**: Build predictive classification models to predict whether an employee will leave the company (`left`), identifying key drivers of churn to help Salifort Motors improve workplace retention strategies.
* **Key Tasks & Methods**:
  * **Exploratory Data Analysis (EDA)**: Investigated distributions and relationships among employee satisfaction, tenure, working hours, and evaluation metrics using data visualization tools.
  * **Feature Engineering & Preprocessing**: Handled categorical variables through encoding, managed outliers, and scaled numerical features to prepare data for machine learning algorithms.
  * **Model Training & Comparison**: Built and evaluated multiple predictive models (including Logistic Regression, Decision Trees, and Random Forest classifiers) to compare predictive performance.
  * **Evaluation Metrics**: Assessed model success using precision, recall, F1-score, and ROC-AUC curves to ensure balanced performance on churn prediction.

---

## 🛠️ Tech Stack & Key Libraries & Functions

* **Language**: Python 3.10+
* **Data Manipulation & Analysis**: `pandas`, `numpy`, `scipy`
  * **Key Functions**: `pd.read_csv()`, `df.describe()`, `df.groupby()`, `np.array()`
* **Statistical Modeling & Machine Learning**: `scikit-learn`, `statsmodels`
  * **Key Functions**: `LogisticRegression()`, `DecisionTreeClassifier()`, `RandomForestClassifier()`, `train_test_split()`, `GridSearchCV()`
* **Model Evaluation & Metrics**: `scikit-learn` metrics
  * **Key Functions**: `accuracy_score()`, `precision_score()`, `recall_score()`, `f1_score()`, `confusion_matrix()`
* **Data Visualization**: `matplotlib`, `seaborn`
  * **Key Functions**: `sns.boxplot()`, `sns.histplot()`, `sns.heatmap()`, `plt.show()`

---

