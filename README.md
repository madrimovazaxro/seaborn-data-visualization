# seaborn-data-visualization
# 📊 Seaborn Data Visualization & EDA Practice

A hands-on exploratory data analysis (EDA) and data visualization notebook built using **Python, Seaborn, Matplotlib, and Pandas**.
This notebook demonstrates practical visualization techniques commonly used in **Machine Learning workflows**, including distribution analysis, relationship analysis, statistical plotting, and plot customization.

---

# 🚀 Overview

This project focuses on learning and applying:

* Exploratory Data Analysis (EDA)
* Statistical visualization
* Seaborn styling & themes
* Distribution analysis
* Relationship analysis
* KDE & regression plots
* Plot customization for professional dashboards

The notebook uses Seaborn’s built-in datasets such as:

* `tips`
* `titanic`
* `iris`

to explore real-world visualization techniques used in data science and machine learning pipelines.

---

# 🛠 Technologies Used

| Category      | Tools               |
| ------------- | ------------------- |
| Programming   | Python              |
| Visualization | Seaborn, Matplotlib |
| Data Analysis | Pandas              |
| Environment   | Jupyter Notebook    |

---

# 📚 Topics Covered

## 1. Seaborn Themes & Styling

Learned how to customize Seaborn visual appearance using:

```python
sns.set_theme()
sns.set_style()
sns.axes_style()
```

### Explored:

* Context scaling (`paper`, `notebook`, `talk`, `poster`)
* Grid styles
* Font scaling
* Spine visibility
* Custom plot aesthetics

---

# 📈 Visualization Techniques

## Histogram (`histplot`)

Used for:

* distribution analysis,
* frequency visualization,
* understanding data spread.

Features explored:

* `bins`
* `kde=True`
* custom themes

Example:

```python
sns.histplot(data=tips, x="total_bill", bins=30, kde=True)
```

---

## Scatter Plot (`scatterplot`)

Used to visualize relationships between variables.

Explored:

* `hue`
* `style`
* `markers`
* `alpha`
* `size`
* custom colors

Example:

```python
sns.scatterplot(
    data=tips,
    x="total_bill",
    y="tip",
    hue="day",
    style="day"
)
```

---

## KDE Plot (`kdeplot`)

Kernel Density Estimation (KDE) used for smooth distribution curves.

Explored:

* `fill=True`
* `bw_adjust`
* line customization
* multiple distributions

Example:

```python
sns.kdeplot(
    data=tips,
    x="total_bill",
    hue="day",
    fill=True
)
```

---

## Box Plot (`boxplot`)

Used for:

* detecting outliers,
* understanding quartiles,
* comparing distributions.

Explored:

* `width`
* `gap`
* `hue`
* legend customization

---

## Violin Plot (`violinplot`)

Combination of:

* box plot
* KDE distribution

Explored:

* `inner='point'`
* density visualization
* grouped distributions

---

## Strip Plot & Swarm Plot

Used for:

* visualizing individual data points,
* avoiding overlap,
* understanding distributions better.

Techniques:

```python
sns.stripplot()
sns.swarmplot()
```

---

## Regression Plot (`regplot`)

Used for:

* trend analysis,
* correlation visualization,
* regression estimation.

Explored:

* confidence intervals (`ci`)
* regression fitting

---

## Joint Plot (`jointplot`)

Combined:

* scatter plots
* KDE
* marginal distributions

Explored:

```python
kind="kde"
fill=True
```

---

# 📊 Key Learning Outcomes

Through this notebook, I strengthened my understanding of:

* Data visualization principles
* Exploratory Data Analysis workflows
* Statistical plotting techniques
* Seaborn customization
* Plot readability & aesthetics
* Relationship analysis between variables
* Distribution interpretation

This practice also improved my ability to create visually clear and professional plots for future Machine Learning and Data Science projects.

---

# 🧠 Machine Learning Relevance

Visualization plays a critical role in Machine Learning workflows:

* detecting outliers,
* understanding feature distributions,
* identifying correlations,
* validating assumptions,
* improving feature engineering decisions.

This notebook serves as foundational practice for:

* Data Science,
* Machine Learning,
* Deep Learning preprocessing workflows.

---

# 📂 Dataset Information

Datasets used from Seaborn:

* Tips Dataset
* Titanic Dataset
* Iris Dataset

Loaded using:

```python
sns.load_dataset()
```

---

# 🎯 Future Improvements

Planned additions:

* Pairplots
* Heatmaps
* Correlation matrices
* Advanced EDA workflows
* Interactive visualizations
* Feature engineering examples
* ML preprocessing visualizations

---

# 👨‍💻 Author

## Roberta Josephina Maddox

Computer Science Student — INHA University

Interests:

* Machine Learning
* Data Engineering
* Backend Development
* Data Visualization
* AI Applications

---

# ⭐ Project Purpose

This notebook was created as part of my continuous learning journey in:

* Data Science,
* Machine Learning,
* Python visualization,
* and analytical thinking.

It reflects hands-on experimentation with professional visualization tools commonly used in real-world ML projects.
