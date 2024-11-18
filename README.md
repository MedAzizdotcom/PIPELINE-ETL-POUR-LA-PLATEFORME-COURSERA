# 📊 Development of Data Warehouse for Coursera 🚀

Welcome to the **Coursera Data Warehouse** project! This repository showcases the process of developing a data warehouse that analyzes user interactions from Coursera's YouTube and Facebook data. Through this project, I explain the steps of the **ETL (Extract, Transform, Load)** process using various tools and technologies. 💡

---

### 🔍 **Project Overview**

This project focuses on extracting, cleaning, and processing Coursera’s social media data (from YouTube and Facebook) to build a data warehouse for efficient analysis and insights. 

- **Data Source**: YouTube & Facebook interactions from Coursera 📺📱
- **Key Technologies**: Python 🐍, Talend ⚡, phpMyAdmin 💻, Export Comments 📥
- **Goal**: Clean and preprocess data, load into a data warehouse, and perform detailed analysis 🔄🔎

---

### 🛠️ **ETL Process Explained**

This section walks you through each step of the ETL process involved in the project.

1. **🔽 Extract**:  
   - We start by extracting data from YouTube and Facebook using API calls and scraping methods.
   - Tools Used: Python 🐍, Talend ⚡, Export Comments 📥

2. **🧹 Transform**:  
   - The raw data is cleaned and transformed using Python and Talend, ensuring that it's in the correct format and meets the quality standards.
   - Key operations: Removing duplicates, normalizing data, and handling missing values.

3. **🔼 Load**:  
   - Finally, we load the cleaned data into the data warehouse using phpMyAdmin, allowing for easy querying and analysis.
   - The data is structured in a way that supports fast and efficient analytics queries.

---

### 📚 **Notebooks and Data Processing**

The following notebooks contain the complete data processing steps:

1. **Data Extraction Notebook**:  
   This notebook contains the steps for extracting raw data from YouTube and Facebook.

2. **Data Cleaning and Transformation Notebook**:  
   Here, you’ll find the code for cleaning, normalizing, and transforming the data into the desired format.

3. **Data Loading Notebook**:  
   The final step of the ETL process: loading the data into the data warehouse using phpMyAdmin.

Feel free to explore the notebooks to dive deep into the process! 🧑‍💻

---

### 💡 **Technologies Used**

- **Python** 🐍 - Data extraction, transformation, and automation.
- **Talend** ⚡ - ETL tool used for data integration.
- **phpMyAdmin** 💻 - Web interface for managing MySQL databases.
- **Export Comments** 📥 - Used for extracting social media comments and interactions.

---

### 🚀 **Getting Started**

To get started, clone this repository and open the respective notebooks for each step of the ETL process. Make sure you have the following installed:

- Python 🐍 (for running the notebooks)
- Talend ⚡ (for ETL process)
- phpMyAdmin 💻 (for MySQL management)

---

### 📈 **Future Work**

In future iterations, I plan to:
- Extend the data sources to include other platforms (e.g., Twitter, Instagram).
- Implement real-time data extraction and processing using stream processing tools like Apache Kafka.

---


### 🤝 **Contributing**

Feel free to fork the repo, submit issues, and send pull requests. Contributions are always welcome!

---

#### 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

