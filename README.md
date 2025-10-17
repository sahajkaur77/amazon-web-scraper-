📦 amazon-web-scraper

A simple Python-based web scraper to fetch product information from Amazon and save it to a CSV file (amazon_data.csv).

🛠️ Features

Scrapes product details from Amazon (e.g. name, price, rating, etc.)

Saves the scraped data into a CSV file

Easy-to-run Python script

📋 Requirements & Setup

This project uses Python 3. You may need a few libraries. Here’s how to set up:

Clone the repository:

git clone https://github.com/sahajkaur77/amazon-web-scraper-.git
cd amazon-web-scraper-


(Optional but recommended) Create & activate a virtual environment:

python3 -m venv venv
source venv/bin/activate     # on Linux/macOS
venv\Scripts\activate        # on Windows


Install required dependencies:

(If you have a requirements.txt, use that. If not, install manually.)

pip install requests beautifulsoup4 pandas

🚀 Usage

Run the scraper script. For example:

python Amazon_scraper.py


After running, you should find the output in:

amazon_data.csv


You can open that file to view the scraped product data in tabular form.

⚠️ Notes & Limitations

Amazon often has anti-scraping measures (CAPTCHA, request throttling, IP blocking).

Use polite scraping: include delays, limit requests, and respect Amazon’s terms of service.

The scraper may break if Amazon changes its site structure (HTML layout).

This script is for educational purposes only — check the legal and ethical implications before heavy use.

🧩 Technologies Used
Technology / Library	Purpose
Python 3	Programming language
requests	Sending HTTP requests
BeautifulSoup	Parsing HTML content
pandas	Handling and exporting data to CSV
🧑‍💻 Contributing

Contributions are welcome! If you'd like to help:

Fork this repository

Create a new branch (git checkout -b feature-name)

Make your changes & commit (git commit -m "Add …")

Push to your fork (git push origin feature-name)

Open a Pull Request here

✉️ Contact

Author: Sahaj

GitHub: sahajkaur77
