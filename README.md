# 🛒 Retail Sales EDA

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset.  
The goal is to understand sales trends, customer behavior, and product category performance.


## 📁 Project Structure

```
📦 retail-sales-eda
│
├── 📂 dataset/
│   ├── retail_sales_dataset.csv
│   └── cleaned_sales.csv
│
├── 📂 notebook/
│   └── EDA_On_Retail_seles_.ipynb
│
├── 📂 images/
│   ├── sales_by_gender.png
│   ├── top_5_categories.png
│   └── daily_sales_trend.png
│
└── README.md
```



## 📊 Visualizations

### **1️⃣ Sales by Gender**
![Sales by Gender](images/sales_by_gender.png)

### **2️⃣ Top 5 Product Categories by Sales**
![Top Categories](images/top_5_categories.png)

### **3️⃣ Daily Sales Trend**
![Daily Sales Trend](images/daily_sales_trend.png)

---

## 🧹 Steps Performed (EDA Workflow)

- Loaded the raw dataset  
- Removed duplicate entries  
- Cleaned missing values  
- Converted `Date` column into datetime format  
- Created a new `Sales` column (Quantity × Price per Unit)  
- Extracted month and day information for trend analysis  
- Grouped data for:
  - Daily sales  
  - Monthly sales  
  - Category-wise sales  
  - Gender-wise sales  
- Generated visualizations using Matplotlib and Seaborn  

---

## 📈 Key Insights

- Female customers contributed slightly more sales than male customers.  
- Electronics and Clothing are the top-selling categories.  
- Daily sales show spikes around mid-year and certain peak shopping days.  

---

## 🛠️ Tools Used

- **Python**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  
- **Jupyter Notebook**  

---

## 📬 Contact

- **LinkedIn:** https://www.linkedin.com/in/tejas-salunkhe-5681b1252/  
- **Email:** salunkhetejas501@gmail.com  
- **GitHub:** https://github.com/TejasML   
