# 📚 E-Commerce Product Scraper and Analyzer (Python + SQLite)

This project demonstrates an end-to-end **data scraping and analysis pipeline** using Python. The data is extracted from the open demo website [Books to Scrape](https://books.toscrape.com), cleaned using Pandas, stored in a **SQLite** database, and analyzed through visualizations using Matplotlib and Seaborn.

---

## 🚀 Features

- ✅ Web scraping with **BeautifulSoup**
- ✅ Data cleaning & transformation with **Pandas**
- ✅ Local database storage using **SQLite**
- ✅ Data querying and analysis in **Jupyter Notebook**
- ✅ Visualizations with **Matplotlib** and **Seaborn**

---

## 📌 Technologies Used

| Tool           | Purpose                         |
|----------------|---------------------------------|
| Python         | Main programming language       |
| BeautifulSoup  | Web scraping                    |
| Requests       | HTTP requests                   |
| Pandas         | Data manipulation               |
| SQLite         | Lightweight database storage    |
| Matplotlib     | Data visualization              |
| Seaborn        | Statistical plotting            |
| Jupyter Notebook | Step-by-step analysis         |

---

## 📊 Data Fields Collected

- `Title` – Book name  
- `Price` – Book price (£)  
- `Availability` – Stock status  
- `Rating` – Star rating (1 to 5)

---

## 📈 Sample Insights

- Most books are priced between **£20 and £50**
- Most ratings fall between **3 and 4 stars**
- Nearly all books are **in stock**

---

## 🗂️ Project Structure

```ecommerce-scraper-analysis/
│
├── ecommerce_scraper_analysis.ipynb   # Main notebook with scraping, cleaning, analysis
├── ecommerce_data.db                  # SQLite database file (auto-generated)
├── README.md                          # This file


