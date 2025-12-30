# 📚 Books Web Scraping Project

This project scrapes book data from the website **https://books.toscrape.com/** using Python with Pandas.

## 🌐 Website Scraped
- https://books.toscrape.com/

## 🔍 Data Scraped
- **Title** – Book name  
- **Price** – Numeric price (currency symbols like £ or $ removed)  
- **Availability** – Stock status  
- **Rating** – Star rating  

📦 **Total Books Scraped:** 1000

## 💰 Price Handling
- Original prices were in GBP (£)
- Currency symbols were removed
- Prices were converted to clean numeric values for easy analysis

## 🛠 Tools Used
- Python  
- Requests  
- BeautifulSoup  
- Pandas  
- Jupyter Notebook  

## 📁 Files
- `Python Web Scraping With Pandas Project.ipynb` → Jupyter Notebook with scraping code  
- `books_to_scrape_1000.csv` → Final scraped dataset  

## 🚀 How to Run
Install required libraries:
```bash
pip install requests beautifulsoup4 pandas
