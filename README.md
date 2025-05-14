# AI-Powered-News-Summeriser

Oberview
An interactive web application that fetches trending news topics, scrapes full articles, and generates concise summaries using state-of-the-art AI models. Built with Streamlit, this tool offers a seamless experience for users to stay informed efficiently.

Features

User Authentication: Secure in-memory login and registration system.

Trending Topics: Fetches news from Google News RSS feeds using feedparser.

Article Extraction: Scrapes and parses full article content from URLs with newspaper.

AI Summarization: Generates summaries using Hugging Face's transformers library.

Responsive UI: Clean and animated interface styled with custom CSS.


Tech Stack

Frontend: Streamlit, Custom CSS

Backend: Python

Libraries:

streamlit – Web interface

newspaper – Article scraping

feedparser – RSS feed parsing

transformers – Text summarization



Installation

1.Clone the repository:
git clone https://github.com/Khushie02/AI-Powered-News-Summeriser.git
cd AI-Powered-News-Summeriser


2.Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


3.Install dependencies:
pip install -r requirements.txt


Running the App
Start the Streamlit application:
streamlit run app.py

