# 📱 Google Play Store Exploratory Data Analysis (EDA)

<img width="1421" height="699" alt="1" src="https://github.com/user-attachments/assets/237ed369-f4a6-4327-859a-549a8f627336" />
<img width="827" height="453" alt="3" src="https://github.com/user-attachments/assets/cc811d8b-0a6f-47e0-a2ef-7a99d144bcb0" />
<img width="838" height="453" alt="2" src="https://github.com/user-attachments/assets/4364fd9c-d424-48aa-8e17-09910536da9c" />
<img width="1489" height="954" alt="output" src="https://github.com/user-attachments/assets/a9b9bbb5-2439-479d-90c8-ba7d6ee55d61" />


## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on the **Google Play Store Dataset** to uncover meaningful insights about mobile applications, user ratings, installs, reviews, pricing, categories, and market trends.

The analysis focuses on understanding app popularity, identifying highly rated applications, comparing install counts across categories, and exploring the relationships between different numerical features.

---

# 🎯 Business Problem

The Google Play Store hosts millions of applications across numerous categories. Understanding user preferences and app performance can help developers, businesses, and marketers make informed decisions.

This project answers important business questions such as:

- Which apps receive the highest and lowest ratings?
- Which app categories dominate in terms of installations?
- How are ratings distributed across the Play Store?
- Are free apps more popular than paid apps?
- How do reviews, installs, and app size relate to one another?
- What trends can be observed in app updates over time?

---

# 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# 📊 Exploratory Data Analysis

## 1️⃣ Univariate Analysis

Analyzed the distribution of important numerical variables including:

- Rating
- Reviews
- Installs
- Size
- Price
- Last Updated
- Day
- Month
- Year

### Key Insights

- Most applications have ratings between **4.0 and 4.7**.
- The majority of apps are free.
- Installs and reviews are highly right-skewed.
- Most applications were updated during **2018**.
- Paid applications represent only a small portion of the dataset.

---

## 2️⃣ Top Rated Applications

Identified the first 10 applications with perfect **5-Star Ratings**.

### Insights

- Multiple applications achieved a perfect user rating.
- Most highly rated apps belong to utility and lifestyle categories.
- High ratings do not necessarily indicate a large install base.

---

## 3️⃣ Lowest Rated Applications

Analyzed the lowest-rated applications available on the Play Store.

### Insights

- Several applications received ratings close to **1.0**.
- Low ratings often indicate poor user experience or outdated functionality.
- Negative user feedback can significantly impact application visibility.

---

## 4️⃣ Most Installed Applications

Compared the most installed applications across popular categories including:

- Communication
- Social
- Productivity
- Tools
- Games

### Insights

- Google applications dominate install counts.
- Social media and communication apps achieve the highest adoption.
- Gaming applications remain among the most downloaded categories.
- Productivity applications maintain consistently high installation numbers.

---

# 📈 Features

- ✔ Data Cleaning
- ✔ Missing Value Handling
- ✔ Duplicate Removal
- ✔ Exploratory Data Analysis
- ✔ Statistical Summaries
- ✔ Distribution Analysis
- ✔ Comparative Visualizations
- ✔ Business Insights

---

# 📊 Business Value

The analysis helps stakeholders:

- Understand user behavior.
- Identify high-performing applications.
- Analyze market competition.
- Discover popular app categories.
- Support data-driven product decisions.
- Improve application marketing strategies.

---

# 📁 Project Structure

```text
Google-PlayStore-EDA
│
├── Google_Play_Store_EDA.ipynb
├── Dataset
│   └── googleplaystore.csv
├── Images
│   ├── univariate-analysis.png
│   ├── top-rated-apps.png
│   ├── lowest-rated-apps.png
│   └── most-installed-apps.png
├── requirements.txt
└── README.md
```

---

# 📸 Visualizations

## 📊 Univariate Analysis

![Univariate Analysis](Images/univariate-analysis.png)

---

## ⭐ Top 10 Highest Rated Applications

![Top Rated Apps](Images/top-rated-apps.png)

---

## 📉 Top 10 Lowest Rated Applications

![Lowest Rated Apps](Images/lowest-rated-apps.png)

---

## 📱 Most Installed Applications by Category

![Most Installed Apps](Images/most-installed-apps.png)

---

# 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Business Insight Generation
- Analytical Thinking

---

# 🔍 Key Findings

- Most Play Store applications maintain ratings above **4.0**.
- Communication and Social apps dominate installation counts.
- Google applications lead in overall installs.
- Reviews and installs exhibit strong positive growth patterns.
- Free applications significantly outnumber paid applications.
- App updates peaked during **2018**, indicating active marketplace growth.

---

# 🚀 Future Improvements

- Perform Correlation Analysis.
- Build Interactive Dashboards using Power BI.
- Create Machine Learning models to predict app ratings.
- Analyze sentiment using user reviews.
- Develop recommendation systems for app categories.

---

# 👨‍💻 Author

**Shaik Arif Hassan**

**Aspiring Data Analyst**

### Skills

- Python
- SQL
- Power BI
- Excel
- Pandas
- NumPy
- Matplotlib
- Data Visualization
- Exploratory Data Analysis (EDA)

---

⭐ **If you found this project helpful, consider giving it a Star ⭐ on GitHub!**
