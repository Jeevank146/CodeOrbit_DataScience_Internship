# CodeOrbit Tech – Data Science Internship

This repository contains the work completed as part of my **Data Science Internship at CodeOrbit Tech**.

The internship tasks cover data cleaning, exploratory data analysis, machine learning, customer segmentation, sales trend analysis, prediction, and business insights.

---

## 📌 Tasks Completed

### Task 1: Data Cleaning & Exploration with Pandas

In this task, a raw student dataset was loaded and cleaned using Pandas.

#### Work Performed

- Loaded the raw CSV dataset using Pandas.
- Checked the number of rows and columns.
- Examined column names and data types.
- Identified missing values.
- Handled missing values in categorical and numerical columns.
- Identified and removed duplicate records.
- Calculated basic statistical measures.
- Analyzed categorical variables using value counts.
- Saved the cleaned dataset for further analysis.

#### Files

- `Task_1.ipynb` – Data cleaning and exploration notebook
- `Task_1_Raw_Data.csv` – Original raw dataset
- `Task_2_3_Cleaned_Data.csv` – Cleaned dataset used for further analysis

---

### Task 2: Exploratory Data Analysis (EDA)

In this task, the cleaned student dataset was explored to understand patterns, relationships, and distributions within the data.

#### Work Performed

- Loaded the cleaned dataset.
- Examined numerical and categorical features.
- Performed exploratory data analysis.
- Created appropriate visualizations.
- Studied relationships between variables.
- Identified important patterns and observations.
- Summarized the findings from the analysis.

#### Files

- `Task_2.ipynb`
- `Task_2_3_Cleaned_Data.csv`

---

### Task 3: Simple Linear Regression

In this task, a Simple Linear Regression model was developed using the cleaned dataset.

#### Work Performed

- Selected suitable features for prediction.
- Prepared the data for machine learning.
- Split the data into training and testing sets.
- Trained a Linear Regression model using Scikit-learn.
- Generated predictions.
- Evaluated the model.
- Visualized the relationship between actual and predicted values.

#### Files

- `Task_3.ipynb`
- `Task_2_3_Cleaned_Data.csv`

---

### Task 4: Customer Segmentation Using K-Means Clustering

In this task, customer segmentation was performed using the **Mall Customers dataset** and the K-Means clustering algorithm.

#### Work Performed

- Loaded the Mall Customers dataset.
- Selected relevant customer attributes.
- Applied K-Means clustering.
- Grouped customers into different segments.
- Visualized the customer clusters.
- Analyzed the characteristics of each customer segment.
- Derived meaningful insights from the clusters.

#### Files

- `Task_4.ipynb`
- `Mall_Customers for task-4.csv`

---

### Task 5: Sales / Trend Prediction

In this task, retail sales data was analyzed to understand sales trends and predict future sales.

#### Work Performed

- Loaded the retail sales dataset.
- Analyzed the sales data.
- Aggregated sales on a daily basis.
- Studied sales trends over time.
- Calculated a 7-day moving average.
- Compared actual sales with the moving average.
- Performed future sales prediction.
- Visualized the actual and predicted sales values.

#### Dataset

The original retail sales dataset is available on Kaggle:

**[Retail Sales Forecasting Data – Kaggle](https://www.kaggle.com/datasets/svizor/retail-sales-forecasting-data?select=sales.csv)**

The original `sales.csv` file is large, so it is not uploaded directly to this GitHub repository.

#### File

- `Task_5.ipynb`

---

### Task 6: Insights Dashboard / Report

In this task, an insights dashboard/report was created using the retail sales dataset.

#### Visualizations Created

1. **Monthly Sales Trend**
2. **Average Sales by Day of Week**
3. **Actual Sales vs 7-Day Moving Average**
4. **Distribution of Daily Sales**

#### Key Insights

- Monthly sales show an overall increasing trend during the analyzed period.
- Friday recorded the highest average sales among the days of the week.
- Sunday recorded the lowest average sales.
- The 7-day moving average helps identify the overall sales trend by reducing daily fluctuations.
- The sales distribution shows variation in daily sales, with some days having unusually high sales.

#### Conclusion

The analysis provides a clear understanding of sales patterns and trends. These insights can help in understanding high-sales periods and support better planning for inventory, promotions, and business operations.

#### Dataset

**[Retail Sales Forecasting Data – Kaggle]([https://www.kaggle.com/datasets/](https://www.kaggle.com/datasets/svizor/retail-sales-forecasting-data?select=sales.csv))**

#### File

- `Task_6.ipynb`

---

# 📊 Datasets Used

| Tasks | Dataset |
|---|---|
| Task 1 | Raw Student Dataset |
| Task 2 & 3 | Cleaned Student Dataset |
| Task 4 | Mall Customers Dataset |
| Task 5 & 6 | Retail Sales Forecasting Dataset |

---

# 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**
- **Google Colab**
- **Jupyter Notebook**

---

# 📁 Repository Structure

```text
CodeOrbit_DataScience_Internship/
│
├── README.md
│
├── Task_1.ipynb
├── Task_1_Raw_Data.csv
│
├── Task_2.ipynb
├── Task_3.ipynb
├── Task_2_3_Cleaned_Data.csv
│
├── Task_4.ipynb
├── Mall_Customers for task-4.csv
│
├── Task_5.ipynb
└── Task_6.ipynb
