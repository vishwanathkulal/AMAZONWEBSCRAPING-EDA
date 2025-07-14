# AMAZONWEBSCRAPING-EDA

# 🎮 Amazon PS5 Product Analysis using Web Scraping & EDA

This project involves scraping product listings of **PlayStation 5 (PS5)** from **Amazon India** and performing **Exploratory Data Analysis (EDA)** to uncover insights about pricing, ratings, and popularity trends among PS5-related products.

---

## 📌 Project Objectives

- Collect real-world PS5 product data using web scraping.
- Clean and preprocess noisy web data.
- Visualize trends in pricing, ratings, and review volume.
- Derive actionable insights using EDA techniques.

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**:  
  - Web Scraping: `requests`, `BeautifulSoup`  
  - Data Handling: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Parsing & Cleaning: `re` (regex)

---

## 📁 Dataset Overview

| Feature        | Description                          |
|----------------|--------------------------------------|
| `Title`        | Product name/title                   |
| `Price`        | Price in INR (₹)                     |
| `Rating`       | Average customer rating (out of 5)   |
| `Review Count` | Number of reviews                    |
| `Description`  | Short product description            |
| `URL`          | Product page URL                     |

- **Shape**: `(40, 6)`
- **Missing Values**:  
  - `Price`: 4 missing  
  - `Review Count`: 1 missing

---

## 🔍 Key Analyses Performed

- **Top 10 Most Reviewed PS5 Products**
- **Rating Distribution Histogram**
- **Price vs Rating Scatter Plot**
- **Correlation Heatmap** for Price, Rating, and Reviews

---

## 📊 Visualizations

- **Bar Chart** showing the top 10 PS5 products with the highest number of reviews.
- **Histogram** illustrating the distribution of average customer ratings across all products.
- **Scatter Plot** representing the relationship between product price and customer rating.
- **Heatmap** showing the correlation matrix between price, rating, and review count.

---
⚠️ Disclaimer
This project is for educational and research purposes only. Web scraping Amazon may violate their Terms of Service. Please use responsibly.

Author 
vishwanath Kulal
