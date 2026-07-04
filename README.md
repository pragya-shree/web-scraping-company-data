# 🕸️ Web Scraping Company Data using Python

## 📌 Overview

This project demonstrates how to build a web scraper using Python to extract company information from a publicly accessible website. The scraped data is cleaned, organized, and stored in a pandas DataFrame for further analysis and exported as a CSV file.

The project showcases the complete workflow of collecting real-world web data, parsing HTML, structuring the extracted information, and preparing it for data analysis.

> **Disclaimer:** This project is for educational purposes only. Data was collected from publicly accessible web pages. Please respect the target website's Terms of Service and `robots.txt` when scraping.

---

## 🚀 Features

* Fetches webpage content using HTTP requests
* Parses HTML using BeautifulSoup
* Extracts company information
* Organizes scraped data into a structured pandas DataFrame
* Exports the dataset to CSV
* Demonstrates real-world web scraping techniques

---

## 🛠️ Tech Stack

* Python
* Requests
* BeautifulSoup (bs4)
* lxml
* Pandas
* Jupyter Notebook

---

## 📂 Project Structure

```text
web-scraping-company-data/
│── webscraping.ipynb
│── companies.csv
│── screenshots/
│   └── dataframe.png
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/pragya-shree/web-scraping-company-data.git
```

Navigate to the project directory:

```bash
cd web-scraping-company-data
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Open the Jupyter Notebook.
2. Run all notebook cells.
3. The scraper will:

   * Download the webpage
   * Parse the HTML
   * Extract company information
   * Create a pandas DataFrame
   * Save the extracted data as `companies.csv`

---

## 📊 Sample Output

The extracted data is organized into a pandas DataFrame containing company information.

Example:

| Company   | Rating | Reviews | Industry    |
| --------- | ------ | ------- | ----------- |
| Company A | 4.3    | 12k     | IT Services |
| Company B | 4.1    | 8k      | Consulting  |

A screenshot of the generated DataFrame is available in the `screenshots` folder.

---

## 📁 Output

* Structured pandas DataFrame
* CSV dataset (`companies.csv`)

---

## 📚 Skills Demonstrated

* Web Scraping
* HTML Parsing
* Data Extraction
* Data Cleaning
* Data Manipulation
* Working with Real-World Data
* Data Export using Pandas

---

## 🔮 Future Improvements

* Scrape multiple pages automatically
* Add error handling and retry logic
* Store data in a SQL database
* Build an interactive dashboard for visualization
* Schedule automated data collection

---

## 👩‍💻 Author

**Pragya Shree**

If you found this project helpful, consider giving it a ⭐ on GitHub!
