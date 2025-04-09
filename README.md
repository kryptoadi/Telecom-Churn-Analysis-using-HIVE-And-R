# 📊 Telecom Churn Analysis using Hive and R

## 📝 Overview

This project analyzes customer churn behavior in the telecom sector using **Apache Hive** for large-scale data processing and **R** for statistical analysis and visualization. The goal is to identify key factors that influence customer churn and develop data-driven insights to help improve customer retention strategies.

---

## 🔍 Key Features

- 💾 **Data Processing with Hive**: Efficient querying and transformation of large telecom datasets stored in a Hadoop ecosystem.
- 📈 **Statistical Analysis in R**: Utilized R for data wrangling, exploratory data analysis, and predictive modeling.
- 📊 **Visualizations**: Created clear and insightful plots to identify churn trends and customer behavior.
- 🤖 **Predictive Modeling**: Built churn prediction models using logistic regression and decision trees to identify customers at risk.

---

## 📂 Dataset Overview

The dataset includes various customer-level features such as:

- Customer ID  
- Gender  
- Senior citizen status  
- Tenure  
- Monthly charges & total charges  
- Contract type and payment method  
- Services used (Internet, phone lines, security, etc.)  
- Churn label (Yes/No)

---

## 🧰 Tech Stack

- **Apache Hive** – for processing and querying large datasets  
- **R (ggplot2, dplyr, caret, etc.)** – for analysis, visualization, and machine learning  
- **Jupyter Notebook** – for step-by-step documentation and execution of the R code  
- **Hadoop HDFS** – for scalable data storage (optional, if applicable)

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/kryptoadi/Telecom-Churn-Analysis-using-HIVE-And-R.git
cd Telecom-Churn-Analysis-using-HIVE-And-R
```

### 2. Set Up Apache Hive
- Install and configure Hive and Hadoop (or use an existing Hadoop ecosystem like HDP or CDP)
- Create a database and table matching the schema of `customer_churn.csv`
- Load the data using:
```sql
LOAD DATA LOCAL INPATH 'customer_churn.csv' INTO TABLE churn_data;
```

### 3. Set Up R Environment
- Install R and RStudio (or use Jupyter with R kernel)
- Install necessary R packages:
```r
install.packages(c("ggplot2", "dplyr", "caret", "e1071"))
```

### 4. Run the Notebook
- Open `Customer churn prediction.ipynb`
- Follow through the sections for data analysis, visualization, and model training

---

## ✅ Results Summary

- **Contract Type**: Customers on month-to-month contracts had a significantly higher churn rate.
- **Monthly Charges**: Users with higher bills tended to churn more.
- **Services**: Add-ons like online security and tech support correlated with **lower churn rates**.
- **Model Accuracy**: Achieved around **80% accuracy** in predicting churn using classification models.

---

## 📚 Project Files

- `customer_churn.csv` – Source dataset  
- `Customer churn prediction.ipynb` – Main analysis notebook  
- `TELECOM CUSTOMER CHURN ANALYSIS REPORT.pdf` – Summary report of the project  
- `README.md` – Project documentation

---

## 🎯 Conclusion

By combining the power of Hive for large-scale data processing and R for in-depth analysis and modeling, this project provides actionable insights to telecom companies aiming to reduce customer churn and improve retention.

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repo  
2. Create your feature branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes  
4. Push to your branch  
5. Open a Pull Request  

---

## 📬 Contact

For queries, suggestions, or collaboration:

- 📧 Email: [kr.rajaditya@gmail.com](mailto:kr.rajaditya@gmail.com)
- 🔗 GitHub: [@kryptoadi](https://github.com/kryptoadi)

---

*Thanks for checking out the project!*
