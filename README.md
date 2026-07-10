# CodeAlpha - Task 1: Web Scraping

## 📌 Internship
CodeAlpha Data Analytics Internship

## 📖 Project Overview
This project demonstrates web scraping using Python and BeautifulSoup.

The script extracts book information from the Books to Scrape website and stores it in a CSV dataset.

## 🎯 Objective
- Extract data from a public website
- Parse HTML using BeautifulSoup
- Store scraped data in CSV format
- Perform basic data collection

## 🛠 Technologies Used
- Python
- BeautifulSoup4
- Requests
- Pandas

## 📂 Dataset
Generated automatically after scraping.

Columns:
- Title
- Price
- Rating
- Availability
## Output
Dataset Saved Successfully!
                              Book Title  Price Availability
0                   A Light in the Attic  51.77     In stock
1                     Tipping the Velvet  53.74     In stock
2                             Soumission  50.10     In stock
3                          Sharp Objects  47.82     In stock
4  Sapiens: A Brief History of Humankind  54.23     In stock
Total Books: 20
Average Price: 38.048500000000004
Highest Price: 57.25
Lowest Price: 13.99

## ▶️ Run

```bash
pip install -r requirements.txt
python src/web_scraper.py
