# Web_Scraping

## Project Overview
This project is a Python-based web scraping tool designed to extract quotes, authors, and tags from the website [quotes.toscrape.com](http://quotes.toscrape.com). The extracted data is stored in a SQLite database for easy access and management.

---

## Features
✅ Scrapes quotes, authors, and tags from the target website.  
✅ Stores data in a structured SQLite database.  
✅ Implements robust error handling for connection issues.  
✅ Efficiently handles multiple records with clean parsing logic.  
✅ Provides sample data output for easy verification.  

---

## Prerequisites
Ensure you have the following installed:
- Python3
- Required Libraries:
  ```bash
  pip install requests beautifulsoup4
  ```

---

## Installation
1. **Clone the Repository**
```bash
git clone <repository_url>
cd web-scraping-tool
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the Script**
```bash
python web_scraper.py
```

---

## Usage
- Upon execution, the script will:
  - Connect to the database.
  - Scrape data from the target website.
  - Save the extracted data into a SQLite database named `quotes_data.db`.
  - Display a sample of saved quotes in the console.

---

## Sample Output
```
-------------------------------------------------------------
Connected to database: quotes_data.db
1. Fetching data from: http://quotes.toscrape.com ...
2. Page loaded successfully!
3. Found 10 quotes!
4. 10 quotes saved to the database!

--------------- Previewing saved quotes: ----------------
"The greatest glory in living lies not in never falling, but in rising every time we fall." - Nelson Mandela [Tags: inspirational, life, perseverance]

"It is our choices, Harry, that show what we truly are, far more than our abilities." - J.K. Rowling [Tags: choices]

--------------- Execution Time: 0.72 seconds -----------------
```

