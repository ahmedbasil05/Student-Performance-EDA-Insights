# 🎓 Student Performance EDA & Insights  

## 📌 Project Overview  
This project performs an in-depth **Exploratory Data Analysis (EDA)** on the *Student Performance Dataset*.  
The objective is to analyze the effect of **demographics, parental background, lifestyle, and study habits** on student outcomes in **Math, Reading, and Writing**.  

---

## 📊 Dataset  
- **Source:** [Kaggle Student Performance Dataset](👉 https://www.kaggle.com/datasets/desalegngeb/students-exam-scores)  
- **Rows:** ~650+  
- **Columns:** Demographics, lifestyle, parental background, study habits, and academic scores.  

**Key Features:**  
- `Gender`, `EthnicGroup`, `ParentEduc`, `LunchType`, `TestPrep`, `ParentMaritalStatus`, `PracticeSport`, `IsFirstChild`, `NrSiblings`, `TransportMeans`, `WklyStudyHours`  
- Scores: `MathScore`, `ReadingScore`, `WritingScore`  

---

## 🛠️ Technologies Used  
- **Python** 🐍  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn  

---

## 🔍 Steps Performed  
✔️ Data loading & inspection (`.info()`, `.describe()`, missing values)  
✔️ Data cleaning (dropped nulls, renamed columns, formatted categories)  
✔️ Gender distribution analysis  
✔️ Grouping scores by **Parent Education** & **Marital Status**  
✔️ Correlation analysis with **heatmap**  
✔️ Outlier detection using **boxplots**  
✔️ Ethnic group distribution with **countplot & pie chart**  

---

## 📈 Visualizations & Insights  
- **Gender Distribution:** Compared male vs female performance  
- **Correlation Heatmap:** Strong correlation among Math, Reading, Writing scores  
- **Parental Education & Marital Status:** Higher education linked to better scores  
- **Outliers:** Detected unusual score patterns via boxplots  
- **Ethnic Group Analysis:** Visualized distributions via countplots & pie charts  

---

## 📊 Results & Key Insights

- Students with higher parental education generally perform better
- Study hours & test preparation significantly affect performance
- Math, Reading, and Writing scores are strongly correlated
- Ethnic group distribution reveals performance variations
- Outliers highlight exceptional performance cases

----

## ⚡ Next Steps: 
Extend the project with Machine Learning models to predict student performance and evaluate feature importance.
