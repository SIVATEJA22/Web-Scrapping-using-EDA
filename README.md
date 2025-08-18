# Web-Scrapping-using-EDA
Extracting data by web scraping NYKAA website, analyzing best category and products of it and visualizing by plotting them using python.
# Nykaa Web Scraping EDA Project

This repository contains an **Exploratory Data Analysis (EDA) project on web scraping the Nykaa website**, focusing on analyzing the best product categories and top products available.

## Project Overview

- **Web Scraping:** Automated data extraction from Nykaa's skincare section using Python (requests, BeautifulSoup).
- **Data Extraction:** Collected product details including name, price, discount, reviews, and other attributes.
- **EDA & Visualization:** Used Pandas, Seaborn, and Matplotlib for data cleaning and visual analysis to identify top categories/products.

## Structure

- **Data-Analytics-Project-EDA-1.ipynb** — Main Jupyter Notebook with complete code, analysis, and outputs.
- **README.md** — Project documentation.
- *(Optional: data files if available)*

## Technologies Used

- Python 3.x
- Jupyter Notebook
- requests
- BeautifulSoup
- pandas
- matplotlib
- seaborn

## How to Run

1. Clone this repository to your local machine.
2. Open `Data-Analytics-Project-EDA-1.ipynb` in Jupyter Notebook.
3. Run cells to see scraping and analysis steps.

## Notes

- For web scraping, ensure you comply with [Nykaa’s Terms of Service](https://www.nykaa.com/).
- Internet connection required for scraping.
- You may need to install required Python packages:
       pip install requests beautifulsoup4 pandas matplotlib seaborn
# Nykaa Web Scraping & EDA Project

This project involves **web scraping the Nykaa skincare product listings** and performing **exploratory data analysis (EDA)** to identify top categories and best-selling products.

---

## Project Steps

### 1. Import Required Libraries
- Install necessary Python packages (`requests`, `bs4`, etc.) in your environment.
- Import modules:  
  `requests`, `BeautifulSoup`, `pandas`, `matplotlib`, `seaborn`.

### 2. Web Scraping Setup
- Define the Nykaa skincare URL for scraping:
url = "https://www.nykaa.com/skin/c/8377"

### 3. Fetch Page Content
- Send an HTTP GET request to the URL using `requests`.
- Check the response status for successful connection (`status_code == 200`).

### 4. Parse HTML Content
- Use `BeautifulSoup` to parse the HTML and extract user-visible product details.

### 5. Extract Product Data
- Identify and extract key product fields:
- Product Name
- Original Price (`MRP`)
- Offer Price
- Discount
- Reviews
- Tags (e.g., FEATURED, BESTSELLER)

### 6. Create Structured Dataset
- Aggregate extracted data into a list of dictionaries.
- Convert this list into a **Pandas DataFrame** for further analysis.

### 7. Data Cleaning
- Handle missing values (e.g., missing prices).
- Convert text fields (e.g., "MRP:₹1190") to numerical formats where needed.
- Standardize field names.

### 8. Exploratory Data Analysis (EDA)
- Analyze key metrics:
- Most reviewed products.
- Highest discounts available.
- Popular FEATURED/BESTSELLER tags.
- Perform visual analysis using `matplotlib` and `seaborn` (bar plots, count plots, price vs. review plots).

### 9. Insights and Findings
- Summarize key findings (e.g., most popular brands/products, trends).
- Discuss product categories with maximum discounts and reviews.

### 10. Save and Present Results
- Display results in notebook markdown cells and tables.
- *(Optional)* Export data as CSV for reuse.

---

## How to Run This Project

1. Clone/download this repository.
2. Open the notebook file (`Data-Analytics-Project-EDA-1.ipynb`) in Jupyter Notebook.
3. Run each cell sequentially to replicate scraping, analysis, and visualization.
4. Ensure you have an active internet connection and required packages installed:
pip install requests beautifulsoup4 pandas matplotlib seaborn

---

## Technologies Used

- Python 3.x
- Jupyter Notebook
- requests
- BeautifulSoup4
- Pandas
- Matplotlib
- Seaborn

---

## Notes

- This project demonstrates web scraping for educational purposes.
- Always respect Nykaa's [Terms of Service](https://www.nykaa.com/) and robots.txt when scraping.

## Author

SIVA TEJA
