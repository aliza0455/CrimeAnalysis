

# 📊 Crime Data Analysis Dashboard

An **interactive Streamlit dashboard** for exploring, visualizing, and analyzing crime data across areas, time, and victim demographics.
This project combines **data cleaning, statistical analysis, probability modeling, and regression techniques** in a single end-to-end data science application.

---

## 🚀 Features

### 🔍 Interactive Filters

* Filter crime records by:

  * **Area**
  * **Crime Type**
  * **Year Range**
* Download filtered data as CSV

---

### 📈 Visual Analytics

* **Bar Chart**: Number of crimes per area
* **Line Chart**: Monthly crime trends
* **Pie Chart**: Victim sex distribution
* **Heatmap**: Crime frequency by area and month
* **Boxplot**: Victim age distribution across top crime types
* **Hourly Pattern**: Crime occurrence by hour of day

---

### 📊 Statistical Analysis

* Victim age:

  * Mean
  * Standard deviation
  * 95% confidence interval
* **Poisson distribution fitting** for daily crime counts
* **Bayes’ Theorem**:

  * ( P(\text{Female} \mid \text{Assault}) )
  * ( P(\text{Assault} \mid \text{Female}) )

---

### 📉 Predictive Modeling

* **Linear Regression Models**:

  1. Crime count vs. year
  2. Average victim age over time
  3. Crime count vs. hour of day
* Regression coefficients and trend visualization included

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit** – interactive web app
* **Pandas & NumPy** – data manipulation
* **Matplotlib & Seaborn** – visualization
* **SciPy** – statistical analysis
* **Scikit-learn** – linear regression modeling

---

## 📦 Installation

```bash
pip install streamlit pandas numpy matplotlib seaborn scipy scikit-learn
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

Make sure `crimedata.csv` is in the same directory as `crimeAnalysis.py`.


---

## 📌 Use Cases

* Exploratory Data Analysis (EDA)
* Crime trend analysis
* Statistical modeling practice
* Academic data science projects
* Interactive dashboard portfolio piece

---

## 📈 Future Enhancements

* Logistic regression or classification models
* Time series forecasting (ARIMA / Prophet)
* Interactive maps (GeoPandas / Folium)
* Crime severity weighting
* Dashboard performance optimization

---

## 👤 Author

**Aliza**
Data Science & Full-Stack Learner
Built as a hands-on analytical and visualization project using real-world crime data.


