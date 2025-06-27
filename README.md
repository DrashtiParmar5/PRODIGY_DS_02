# PRODIGY_DS_02
# 🧹 Titanic Data Cleaning & EDA — Task 2 (Internship Project)

## 📝 Task -2 Description

**Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.**

This project is part of my ongoing internship where I was assigned the task of understanding data preprocessing and discovering insights through exploratory data analysis. I chose the dataset for this task, which is widely used for practicing classification, missing data handling, and visualization techniques.

---

## 🗂️ Dataset Information

The dataset used is [`test.csv`](./test.csv), a subset of the original Titanic dataset containing key features:

- **PassengerId**: Unique ID of each passenger  
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- **Name, Sex, Age**: Demographics  
- **SibSp, Parch**: Family onboard  
- **Ticket, Fare**: Travel and payment information  
- **Cabin, Embarked**: Boarding details

---

## ✅ Task Objectives

### 🔹 Data Cleaning Performed

1. **Initial Data Inspection**:
   - Displayed `.head()`, `.tail()`, `.info()`, and `.describe()` to understand the dataset.

2. **Missing Values Treatment**:
   - Checked for missing values using `isnull().sum()`.
   - Filled missing **Age** values with the **mean**.
   - Replaced missing **Cabin** entries with **"Unknown"**.
   - Verified remaining null values post-cleaning.

3. **Data Deduplication**:
   - Checked for and confirmed there were **no duplicate rows**.

---

## 📊 Exploratory Data Analysis (EDA)

Using `Matplotlib` and `Seaborn`, multiple visualizations were generated to explore variable relationships:

1. **Univariate Analysis**:
   - Age distribution
   - Passenger class counts
   - Fare distribution

2. **Bivariate Analysis**:
   - Relationship between Age and Passenger Class
   - Visual correlation between numerical features using **heatmaps**

3. **Insights Extracted**:
   - **Pclass 3** had the highest number of passengers.
   - Passengers aged **20–40** formed the bulk of the dataset.
   - Higher **fare** generally correlated with **lower passenger class numbers** (1 being the most expensive).

---

## 🛠️ Tools & Libraries Used

- **Python 3**
- **Pandas** for data handling
- **Matplotlib & Seaborn** for visualization
- **Jupyter Notebook** for step-by-step analysis

---

## 📌 Key Learnings

- Gained experience in handling real-world messy datasets using Python.
- Practiced essential EDA techniques to uncover patterns and anomalies.
- Understood data distribution and relationships between features.
- Strengthened skills in Python-based data visualization and analysis.

---

## 🙋‍♀️ Author

**Drashti Parmar**  
🎓 Computer Engineering | 📊 Aspiring Data Scientist  
📬 [LinkedIn Profile](https://www.linkedin.com/in/drashti-parmar-683358320/)

---

## 🔗 Acknowledgements

Thanks to my internship mentors for assigning this insightful task and helping me develop hands-on data science capabilities.
