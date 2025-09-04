# Web_Scraping-Using-Python

A Python-based web scraping toolkit that demonstrates scraping web pages, parsing content, and data extraction. Ideal for learning Python web scraping fundamentals.

---

##  Project Structure
Web_Scraping-Using-Python/
├── scrape.py # Handles HTTP requests and raw HTML download
├── parse.py # Parses HTML content and extracts data
├── main.py # Script orchestrating the scraping+parsing pipeline
├── requirements.txt # Python dependencies
├── .env # (Optional) Stores environment variables like URLs or selectors
└── README.md # This documentation

---
##  Features

- **Modular Design**: Separate scraping and parsing logic for flexibility.
- **Configurable**: Easily add or tweak selectors or URLs via `.env` or inline variables.
- **Educational Workflow**: Understand the full cycle—from HTTP requests to parsed output.

---

##  Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/ManobiSaiRam/Web_Scraping-Using-Python.git
cd Web_Scraping-Using-Python

### 2.Create and Activate a Virtual Environment
python3 -m venv venv
# macOS/Linux
source venv/bin/activate
# Windows (PowerShell)
venv\Scripts\Activate.ps1

### 3. Install Dependencies
pip install -r requirements.txt

### 4.Configure .env

If your scripts rely on configurable parameters (e.g. URL targets or HTML selectors), you can store them in .env using the format:
web_scraper = " "

### 5. Run the Workflow
streamlit run main.py
---
### Note:You need to add Web Driver whenever you used this file and run it through streamlit using the code "Streamlit run main.py"



