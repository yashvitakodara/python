# 🕷️ Python Web Scraping & Data Extraction Portfolio

A collection of automated web scraping, web crawling, and API extraction pipelines built in Python. Each notebook demonstrates end-to-end extraction from raw web sources into clean, structured datasets ready for analysis.

## 📂 Featured Projects

| Notebook | Target & Use Case | Techniques & Tools |
| :--- | :--- | :--- |
| **`amul_icecreams.ipynb`** | Amul Ice Cream Product Catalog (names, quantities, pack sizes) | `Selenium`, `BeautifulSoup4`, dynamic DOM handling |
| **`limeroadsocks.ipynb`** & **`limeroad.ipynb`** | LimeRoad E-Commerce Product Listings & Pricing | `Selenium`, `BeautifulSoup4`, multi-page pagination |
| **`largerevenueusa.ipynb`** | US Largest Companies by Revenue Directory | `requests`, `BeautifulSoup4`, HTML table parsing & cleaning |
| **`quotes.hiddenapi.ipynb`** | Dynamic Infinite-Scroll Site via Backend API | `requests`, JSON API reverse-engineering |
| **`laptoppagin.ipynb`** & **`btspagination.ipynb`** | Multi-Page E-Commerce Catalog Pagination | `requests`, `BeautifulSoup4`, URL parameter & next-page loops |
| **`booksscraped.ipynb`** & **`webcrawlledbooks.ipynb`** | Full-Site Book Catalog Crawler (titles, ratings, stock, prices) | `BeautifulSoup4`, `urllib.parse` (`urljoin`), multi-page crawling |

## 🛠️ Core Capabilities Demonstrated
* **Dynamic JavaScript Rendering:** Automating headless Chrome via `Selenium` to extract content loaded asynchronously.
* **Hidden API Extraction:** Inspecting network requests to pull structured JSON directly without heavy browser overhead.
* **Multi-Page Crawling & Pagination:** Handling relative URL resolution (`urljoin`), next-button traversal, and query pagination.
* **Data Structuring:** Cleaning text, resolving missing tags, and exporting tabular outputs with `pandas`.

## 🚀 How to Run
1. Open any `.ipynb` file directly in **Google Colab** or **Jupyter Notebook**.
2. Install dependencies if running locally:
   ```bash
   pip install requests beautifulsoup4 selenium pandas lxml
