# 05-Analyze-files-with-Spark
## Analyze data in a data lake with Spark
Apache Spark is an open source engine for distributed data processing, and is widely used to explore, process, and analyze huge volumes of data in data lake storage. Spark is available as a processing option in many data platform products, including Azure HDInsight, Azure Databricks, and Azure Synapse Analytics on the Microsoft Azure cloud platform. One of the benefits of Spark is support for a wide range of programming languages, including Java, Scala, Python, and SQL; making Spark a very flexible solution for data processing workloads including data cleansing and manipulation, statistical analysis and machine learning, and data analytics and visualization.



## 📝 Purpose

This lab demonstrates how to analyze data files using Apache Spark in Azure Synapse Analytics. You'll learn how to load data from files, transform it using Spark DataFrames, and perform queries and visualizations.

## 🚀 Key Concepts

- Reading and analyzing file-based datasets with Spark
- Transforming data using DataFrame operations
- Performing aggregations and filters
- Querying data with Spark SQL
- Visualizing data using Spark’s built-in chart options and Python libraries

## 🛠️ Technologies Used

- **Azure Synapse Analytics**
- **Apache Spark / PySpark**
- **Spark SQL**
- **Pandas**
- **Matplotlib & Seaborn** (for advanced visualizations)

## 📂 Lab Workflow Summary

1. **Read Data from File**
   - Load structured data into a Spark DataFrame using Synapse.
   
2. **DataFrame Operations**
   - Select specific columns.
   - Filter rows based on conditions.
   - Count total and distinct values.

3. **Aggregations and Grouping**
   - Use `.groupBy()` and `.sum()` to compute totals.
   - Extract and group by year using Spark functions.

4. **Spark SQL Queries**
   - Register DataFrames as temp views.
   - Use SQL queries (`spark.sql(...)`) to retrieve and analyze data.
   - Use `%%sql` magic to run SQL directly in notebook cells.

5. **Visualization**
   - Switch from table to chart view in Synapse notebooks.
   - Create charts using `matplotlib` and `seaborn`.

6. **Cleanup**
   - Delete Azure Synapse resources to avoid extra costs.

## 📊 Sample Visuals Created

- Bar chart of total product sales
- Yearly revenue trends (bar & line charts)
- Pie chart showing orders per year

## ✅ Learning Outcomes

By completing this lab, you will:

- Understand how to work with file-based data using Spark in Synapse
- Gain skills in DataFrame transformations and SQL-based queries
- Learn to visualize data with built-in and external libraries

## 🧹 Cleanup Reminder

Don't forget to delete your Azure resource group after finishing the lab to prevent unnecessary charges.

---

## Screenshots
![lab51](https://github.com/user-attachments/assets/8e76ca16-a965-4d54-a9d2-b686bc37e776)
![lab52](https://github.com/user-attachments/assets/2aa0dda5-1299-4851-bf6d-876d07428787)
![lab53](https://github.com/user-attachments/assets/a9a09f1b-97e2-452c-b4fc-5f7c0b5fd051)
![lab53sparkpoolfirst](https://github.com/user-attachments/assets/ef5c5da4-d547-4388-bcd1-4dd1d749304c)
![lab53sparkpoolfirst2](https://github.com/user-attachments/assets/246c4041-5dca-4f52-9ed8-89d14c7c559f)
![lab53sparkpooll](https://github.com/user-attachments/assets/303ceb8c-e6fe-4083-ba7b-78872afdc737)
![lab53sparkpooll5](https://github.com/user-attachments/assets/7d8bee6b-0c0d-4c37-86bb-bfda969db91d)
![lab53sparkpooll6](https://github.com/user-attachments/assets/4af6328f-9042-4b1d-8b0e-2689b63a5ee1)
![lab5charts](https://github.com/user-attachments/assets/d5e183c4-f059-4093-b562-e0f05308e3c7)
![lab5charts2](https://github.com/user-attachments/assets/01c5c21f-e3d5-469d-9512-916f6c960356)
![lab5charts3](https://github.com/user-attachments/assets/48fdbe02-c858-4293-8e36-2269b97bc9ef)
![lab5charts4](https://github.com/user-attachments/assets/2db3b580-591b-4429-bd48-9b7963fbfa43)


