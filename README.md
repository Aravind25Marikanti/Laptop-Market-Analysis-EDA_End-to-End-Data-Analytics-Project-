# 💻 Laptop Market Analysis – Flipkart Web Scraping & Data Analysis

## 📌 Project Overview

This project focuses on collecting, cleaning, transforming, and analyzing laptop product data from **Flipkart** using Python.

The objective is to understand the laptop market by analyzing product features, specifications, pricing, ratings, and other important attributes. The project demonstrates an end-to-end data analytics workflow starting from **web scraping to data cleaning, feature extraction, and exploratory data analysis**.

---

## 🎯 Business Problem Statement

The laptop market contains a wide range of products with different prices, processors, RAM, storage, display sizes, ratings, and specifications.

For customers and retailers, it can be difficult to compare laptops and understand how different specifications influence product pricing and ratings.

This project aims to analyze laptop product data collected from Flipkart to identify:

- Price variations across different laptop specifications
- Popular processor types and brands
- RAM and storage configurations
- Display size and resolution patterns
- Relationship between price and laptop specifications
- Rating and review patterns
- Key features available across different laptop categories

The analysis can help customers make better purchasing decisions and provide insights into laptop market trends.

---

## 📊 Project Objectives

The major objectives of this project are:

- Collect laptop product data from Flipkart
- Scrape product information using Python
- Extract relevant product features from the scraped data
- Clean and preprocess the raw dataset
- Handle missing and inconsistent values
- Extract structured information such as processor, RAM, storage, and display specifications
- Perform exploratory data analysis
- Identify patterns and trends in laptop pricing
- Analyze relationships between specifications and price
- Generate meaningful business insights from the dataset

---

## 🛠️ Technologies & Tools Used

- **Python**
- **Pandas**
- **NumPy**
- **Requests**
- **BeautifulSoup**
- **Regular Expressions (Regex)**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **GitHub**

---

## 🔄 Project Workflow

The project follows an end-to-end data analytics workflow:

    Flipkart Laptop Category
              ↓
          Web Scraping
              ↓
          Raw Dataset
              ↓
         Data Cleaning
              ↓
       Feature Extraction
              ↓
       Data Transformation
              ↓
    Exploratory Data Analysis
              ↓
       Data Visualization
              ↓
       Business Insights

---

## 🕷️ 1. Web Scraping

The **Laptop category on Flipkart** was selected as the data source.

The scraping process involved:

1. Selected the **Laptop category on Flipkart** as the data source.
2. Identified the required **product-level fields** to collect.
3. Sent requests to the **laptop listing pages** using Python.
4. Extracted product details from the **HTML content** using BeautifulSoup.
5. Dynamically accessed **multiple pages** to collect more products.
6. Combined the collected records into a **single dataset**.
7. Saved the scraped data for further cleaning and analysis.

### Data Collected

The scraped dataset contains product-level information such as:

- Product Name
- Price
- Rating
- Number of Reviews
- Product Features
- Product URL
- Other available product details

---

## 📁 2. Raw Dataset Overview

The raw dataset contains the information collected directly from Flipkart during the web scraping process.

The `features` column contains multiple laptop specifications in text format. These specifications were later processed to extract individual attributes.

The raw dataset includes information related to:

- Processor
- RAM
- Storage
- Display
- Operating System
- Graphics
- Product Price
- Ratings
- Reviews
- Other laptop specifications

The raw data required further cleaning and transformation before analysis.

---

## 🧹 3. Data Cleaning

The scraped data was cleaned and prepared for analysis using **Pandas** and Python.

The major data cleaning steps included:

- Checking dataset dimensions
- Checking column names and data types
- Identifying missing values
- Removing duplicate records
- Handling inconsistent values
- Cleaning price values
- Cleaning rating-related columns
- Standardizing text values
- Removing unwanted characters and symbols
- Converting columns into appropriate data types
- Preparing the dataset for feature extraction

---

## 🔍 4. Feature Extraction

Several laptop specifications were stored together inside the `features` column. Therefore, **Regular Expressions (Regex)** were used to extract individual product attributes.

### Extracted Features

The important features extracted from the laptop specifications include:

- Processor
- RAM
- Storage
- Display Size
- Display Resolution
- Operating System
- Graphics
- Other relevant specifications

The extracted information was stored in separate columns to make the dataset structured and easier to analyze.

---

## 💻 5. Processor Extraction

Processor information was extracted from the laptop feature descriptions using **Python and Regular Expressions**.

The processor analysis helps identify:

- Processor brands
- Processor families
- Processor categories
- Most common processors
- Processor distribution
- Price differences across processor categories

---

## 🖥️ 6. Display Analysis

Display-related information was extracted from the laptop product specifications.

The analysis includes:

- Display size
- Display dimensions
- Display-related specifications
- Distribution of laptop display sizes

Display measurements were standardized where possible to make comparisons easier during analysis.

---

## 💾 7. RAM & Storage Analysis

RAM and storage specifications were extracted from the product features and converted into structured columns.

The analysis helps identify:

- Common RAM configurations
- Common storage capacities
- Popular laptop configurations
- Relationship between RAM and price
- Relationship between storage and price

---

## 💰 8. Price Analysis

Laptop prices were cleaned and converted into numerical values for analysis.

Price analysis helps understand:

- Minimum laptop price
- Maximum laptop price
- Average laptop price
- Price distribution
- Price differences across specifications
- Budget laptop segments
- Premium laptop segments

---

## 📈 9. Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to identify patterns, trends, and relationships within the laptop market.

The analysis focuses on:

- Price distribution
- Processor distribution
- RAM distribution
- Storage distribution
- Display size distribution
- Rating distribution
- Review patterns
- Specification versus price relationships

Various visualizations were created using **Matplotlib** and **Seaborn** to make the findings easier to understand.

---

## 📊 10. Data Visualization

Charts and graphs were created to analyze and communicate the findings effectively.

The visualizations include:

- Price Distribution
- Processor Distribution
- RAM Distribution
- Storage Distribution
- Display Size Distribution
- Price vs RAM
- Price vs Storage
- Price vs Rating
- Processor vs Average Price
- Other specification-based comparisons

---

## 💡 11. Key Business Insights

The analysis helps identify important insights about the laptop market, including:

- Most common processor categories
- Most frequently available RAM configurations
- Popular storage capacities
- Laptop price distribution
- Price differences across processor categories
- Relationship between RAM and laptop price
- Relationship between storage and laptop price
- Specifications associated with premium-priced laptops
- Customer rating and review patterns
- Popular laptop configurations in the collected dataset

---

## 📂 12. Project Structure

    Laptop-Market-Analysis/
    │
    ├── 📓 Laptop_Market_Analysis_Project_scraped1.ipynb
    │
    ├── 📓 Laptop_Market_Analysis_Project_clean&Analysing2.ipynb
    │
    ├── 📄 scrapped_data.csv
    │
    ├── 📄 Final_Cleaned_Dataset.csv
    │
    ├── 📄 Final_Cleaned_Dataset.csv
    │
    └── 📄 README.md
