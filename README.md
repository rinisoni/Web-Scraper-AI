# Web-Scraper-AI
A simple AI-powered tool that lets you scrape any website, clean up its content, and ask questions about it — all from your browser.

---------------------------------------------------------------------------------------------------------------------------------------------------
🚀 Features
🌐 Scrapes content from any URL using Selenium

🧹 Cleans and extracts only useful body text

🤖 Uses LLaMA 3 (via Ollama) to parse and extract information based on your instructions

🖼️ Built with an intuitive Streamlit interface

--------------------------------------------------------------------------------------------------------------------------------------------------
🛠️ How to Run
1. Install dependencies
pip install -r requirements.txt

2. Download and place ChromeDriver
Make sure chromedriver is placed at:
/home/hiren/Desktop/WebScraperAI/chromedriver-linux64/chromedriver
Or update the path in scrape.py if it's different.

3. Start the app
streamlit run main.py

----------------------------------------------------------------------------------------------------------------------------------------------------

🧠 Example Usage
1. Enter a website URL

2. View the cleaned body content

3. Type a query like:
"List all product names with prices"

4. Get AI-parsed results from the page
   
--------------------------------------------------------------------------------------------------------------------------------------------------
🧩 Tech Stack
Python

Streamlit

Selenium + BeautifulSoup

LangChain + Ollama + LLaMA 3

--------------------------------------------------------------------------------------------------------------------------------------------------
📦 Requirements
Python 3.8+

Ollama + LLaMA 3 installed and running locally

