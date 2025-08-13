# 🎬 **Netflix Content Analysis and Recommendation System**

## 📌 **Project Overview**
This project analyzes **Netflix’s content library** to uncover **patterns**, **trends**, and **similarities** between titles.  
It combines **data cleaning**, **exploratory data analysis (EDA)**, **feature engineering**, and **machine learning** to:

- 📊 **Provide visual insights** into Netflix content  
- 🎯 **Recommend similar titles** based on genres and directors  
- 📈 **Forecast future content releases**  
- 🏷 **Classify** whether a title is a **Movie** or **TV Show**

---

## 🔍 **Key Components**

### **1️⃣ Data Cleaning and Preparation**
- 🧹 **Handled missing values** to ensure reliable analysis  
- 🗑 **Removed duplicate entries** to maintain data quality  
- 📅 **Converted date columns** to `datetime` format for time-series analysis  

### **2️⃣ Exploratory Data Analysis (EDA)**
- 📊 Visualized **Movies vs TV Shows** distribution  
- 📌 Identified the **most frequent genres**  
- ☁️ Created a **word cloud** to show genre frequency  

### **3️⃣ Feature Engineering**
- 📑 Counted **number of genres** per title  
- ⏱ Extracted **numeric duration** (minutes for movies, seasons for TV shows)  
- 📆 Extracted **year** and **month added** from `date_added`  
- 🔖 Created a binary label **`is_tv_show`** (`1 = TV Show`, `0 = Movie`)  

### **4️⃣ Machine Learning Models**

#### **🎥 Content-Based Recommendation**
- 🔗 Combined **genres** and **director** into a single text feature  
- 🧮 Used **CountVectorizer** to convert text into numeric vectors  
- 📐 Applied **cosine similarity** to recommend similar titles  

#### **📅 Time-Series Forecasting**
- 📊 Grouped releases by **year** and applied **ARIMA** for prediction  
- 📈 Forecasted content releases for the **next 5 years**  
- 🖼 Visualized **actual vs predicted releases**  

#### **🤖 Classification**
- 🏷 Trained a **Random Forest Classifier** to predict whether a title is a **Movie or TV Show**  
- 📏 Evaluated with **accuracy score**, **classification report**, and **confusion matrix**  

---

## 🛠 **Technologies Used**
**Language:** Python  

**Libraries & Tools:**  
- 🗃 **Data Handling:** Pandas, NumPy  
- 📊 **Visualization:** Matplotlib, Seaborn, WordCloud  
- 🤖 **Machine Learning:** scikit-learn  
- ⏳ **Time Series Modeling:** Statsmodels (**ARIMA**)  

---

## 📌 **Conclusion**
This project demonstrates a **complete data science workflow** — from **cleaning and exploration** to **predictive modeling** and **recommendation**.  
It highlights the use of **machine learning** and **analytics** to:
- Understand content distribution patterns  
- Predict future content releases  
- Provide personalized recommendations  

---
