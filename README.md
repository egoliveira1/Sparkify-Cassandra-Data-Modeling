# **Sparkify-Cassandra-Data-Modeling**

## **Summary of the project**

### **Problem**
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app. They'd like to create an Apache Cassandra database which can make queries on song play data to answer the questions.

### **Solution**
I developed the solution modeling the data with Apache Cassandra and making an ETL pipeline using Python. The ETL pipeline transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.