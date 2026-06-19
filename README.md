# 📊 Customer Purchase Propensity Analysis & Data Preprocessing Pipeline

A complete **Data Preprocessing and Exploratory Data Analysis (EDA)** project focused on understanding customer purchasing behavior using multi-source structured data.  

This project demonstrates how raw business/customer data can be collected, analyzed, cleaned, visualized, and prepared for future machine learning models such as customer purchase prediction systems. 🚀

---

## 📌 Project Overview

In real-world business systems, customer data comes from multiple sources and usually contains inconsistencies, missing patterns, and hidden behavioral insights.  

The goal of this project is to build a preprocessing and analysis pipeline that:

✅ Collects data from different formats  
✅ Analyzes customer purchase behavior  
✅ Visualizes important business patterns  
✅ Detects unusual/outlier values  
✅ Prepares data for future predictive machine learning models  

This project simulates an **E-Commerce Customer Analytics System**. 🛒

---

## ❓ Problem Statement

Businesses often struggle to understand:

- 💰 Which customers spend more money?  
- 💳 What payment methods are most used?  
- 📈 How customer income affects purchasing behavior?  
- ⚠️ Are there unusual spending patterns in the dataset?  
- 🤖 How can raw customer data be prepared for machine learning?  

This project solves these problems through preprocessing and exploratory analysis.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| 🐍 Python | Main programming language |
| 📓 Jupyter Notebook | Development environment |
| 🐼 Pandas | Data manipulation |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Data visualization |
| 🤖 Scikit-Learn | Preprocessing utilities |
| 🗄️ SQLite | SQL database operations |
| 📁 JSON | Structured transaction data |
| 🌐 Requests API | External data fetching |

---

## 📂 Dataset Sources

The project integrates customer-related data from multiple sources:

- 📄 `customers.csv` → Customer demographic data  
- 📑 `transactions.json` → Customer transaction records  
- 🗄️ `products.sql` → Product-related structured data  
- 🌍 API Source → Additional external customer information  

Data is merged using common identifiers:

- customer_id  
- product_id  

---

## 🔄 Project Workflow

The project follows the following pipeline:

```text
Data Collection
      ↓
Data Integration
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Distribution Analysis
      ↓
Relationship Analysis
      ↓
Outlier Detection
      ↓
Dataset Preparation for Machine Learning
```

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand customer behavior and identify important business patterns.

The following visualizations were created.

### 1️⃣ Income Distribution Analysis 💵

This histogram shows how customer income is distributed across the dataset.

<img width="537" height="365" alt="Screenshot 2026-06-19 170332" src="https://github.com/user-attachments/assets/10666e1b-3bd7-47a2-bd42-c3745031b6d5" />


---

### 2️⃣ Transaction Amount Distribution Analysis 💸

This graph helps analyze customer spending frequency and transaction value patterns.

<img width="521" height="351" alt="Screenshot 2026-06-19 170525" src="https://github.com/user-attachments/assets/a2c30438-31ff-46f0-807a-17d99f54bdd1" />


---

### 3️⃣ Gender Distribution Analysis 👥

This chart shows demographic customer distribution based on gender categories.

<img width="530" height="360" alt="Screenshot 2026-06-19 170626" src="https://github.com/user-attachments/assets/d1584d1a-3401-4ae8-b758-7d593a14dab5" />


---

### 4️⃣ Payment Mode Distribution Analysis 💳

This graph helps identify which payment methods customers prefer while purchasing.

Payment methods analyzed:

- UPI 📱  
- Credit Card 💳  
- Debit Card 💰  
- Cash 💵  

<img width="524" height="382" alt="Screenshot 2026-06-19 170759" src="https://github.com/user-attachments/assets/5d502c93-3060-45eb-b4f7-85d6a407a508" />


---

### 5️⃣ Income vs Transaction Amount Relationship 📈

Scatter plot analysis helps study whether high-income customers spend more money compared to low-income customers.

<img width="536" height="358" alt="Screenshot 2026-06-19 170813" src="https://github.com/user-attachments/assets/210d3b23-6cdf-4f79-a4cd-397e0a506212" />

---

## 📦 Outlier Detection Analysis

Outlier detection was performed to identify abnormal values that can negatively affect future machine learning models.

### 6️⃣ Income Outlier Detection ⚠️

Boxplot used to identify extreme income values present in the customer dataset.

<img width="529" height="347" alt="Screenshot 2026-06-19 170826" src="https://github.com/user-attachments/assets/1be12486-8fc9-4671-b038-2c7d44da2716" />


---

### 7️⃣ Transaction Amount Outlier Detection 🚨

Boxplot used to identify unusually high or low transaction values.

<img width="529" height="346" alt="Screenshot 2026-06-19 170838" src="https://github.com/user-attachments/assets/1701effb-0ee3-4428-8b32-8f7c1cb561d4" />


---

## ⚙️ Techniques Implemented

The project uses the following data preprocessing and analysis techniques:

- 📥 Multi-source Data Import  
- 🔗 Data Integration  
- 🧹 Data Cleaning  
- 📊 Exploratory Data Analysis (EDA)  
- 📉 Histogram Analysis  
- 📌 Bar Chart Analysis  
- 📈 Scatter Plot Relationship Analysis  
- 👤 Customer Behavior Analysis  
- 📦 Outlier Detection using Boxplots  
- 🔍 Business Pattern Identification  

---

## 🔍 Key Insights Discovered

Important insights found during analysis:

- 💰 Customer income distribution patterns were identified  
- 🛍️ Customer transaction amount patterns were analyzed  
- 💳 Payment mode usage trends were discovered  
- 👥 Gender-based customer distribution was analyzed  
- 📈 Income and transaction amount relationship was visualized  
- ⚠️ Outliers were identified in income and transaction data  

---

## 🚀 Future Improvements

This project can be extended further by implementing:

- Missing Value Imputation  
- Feature Engineering  
- Feature Encoding  
- Data Scaling  
- Machine Learning Model Training  
- Customer Purchase Prediction Model  

Possible models:

- Logistic Regression  
- Random Forest  
- XGBoost  
- Decision Trees  

---

## 🎯 Learning Outcomes

Through this project, I learned:

- 🧠 Real-world data preprocessing pipeline design  
- 📂 Working with multiple data sources  
- 📊 Exploratory data analysis techniques  
- 📈 Business data visualization  
- 👥 Customer behavior analytics  
- 📦 Outlier detection methods  
- 🤖 Preparing data for machine learning workflows  

---

## 📁 Project Structure

```text
Project Folder
│
├── customers.csv
├── transactions.json
├── products.sql
├── DataPreprocessing.ipynb
├── README.md
```


## ✨ Final Note

This project demonstrates how raw business data can be transformed into meaningful insights through preprocessing and exploratory data analysis before building machine learning systems.  

⭐ If you like this project, feel free to explore and improve it further.
