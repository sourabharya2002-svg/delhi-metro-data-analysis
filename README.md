# 🚇 Delhi Metro Data Analysis

## 📌 Project Overview

This project performs data cleaning, preprocessing, and visualization on Delhi Metro data to extract insights about passenger flow, revenue, and station performance.

---

## 📂 Dataset

The dataset used in this project:

📁 [[Download Dataset](data/delhi_metro_cleaned_data.csv)] 

### Columns:

* Ticket_Type
* From_Station
* To_Station
* Passenger_Count
* Cost
* Revenue

---

## 🧹 Data Cleaning

* Handled missing values using mode and median
* Removed extra spaces using `.str.strip()`
* Created new feature: **Profit = Revenue - Cost**

---

## 📊 Analysis & Visualization

* Passenger distribution
* Revenue vs Passenger count
* Profit analysis
* Station-wise insights

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🚀 How to Run

```bash
git clone https://github.com/sourabharya2002-svg/delhi-metro-data-analysis
cd delhi-metro-data-analysis
pip install -r requirements.txt
jupyter notebook
```

---

## 📈 Key Insights

* Identified high traffic stations
* Found profitable routes
* Analyzed passenger behavior

---

## 📌 Author

Sourabh Arya

