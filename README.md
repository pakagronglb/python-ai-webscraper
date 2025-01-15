# 🐍 AI-Powered Web Scraper

![banner](./ai-python-scraper.gif)

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![Brightdata](https://img.shields.io/badge/Brightdata-API-brightgreen?style=for-the-badge)](https://brightdata.com/)
[![Ollama](https://img.shields.io/badge/Ollama-AI-green?style=for-the-badge)](https://ollama.ai/)
[![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4-orange?style=for-the-badge)](https://www.crummy.com/software/BeautifulSoup/)
[![Requests](https://img.shields.io/badge/Requests-latest-red?style=for-the-badge)](https://requests.readthedocs.io/)
[![dotenv](https://img.shields.io/badge/python--dotenv-latest-yellow?style=for-the-badge)](https://github.com/theskumar/python-dotenv)

## 📖 Overview
This project is an AI-powered web scraper that intelligently extracts and processes information from websites using Brightdata's API for reliable data collection. Built following the tutorial by [Tech With Tim](https://www.youtube.com/watch?v=Oo8-nEuDBkk).

## 📚 Features
- Intelligent web scraping using BeautifulSoup4
- Professional web scraping with Brightdata API
- AI-powered content analysis with Ollama
- Environment variable management for secure configuration
- Custom parsing logic for extracted data

## 📚 Prerequisites
- Python 3.9 or higher
- Ollama installed and running
- Brightdata API credentials
- Required Python packages (see requirements.txt)

## 📦 Installation
1. Clone the repository
```bash
git clone https://github.com/pakagronglb/python-ai-webscraper.git
cd python-ai-webscraper
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Set up environment variables
Create a `.env` file in the root directory and add your configuration:
```
OLLAMA_API_URL=your_ollama_api_url_here
BRIGHTDATA_USERNAME=your_username_here
BRIGHTDATA_PASSWORD=your_password_here
```

## 🚀 Usage
Run the main script:
```bash
python main.py
```

## 🙏🏻 Credits
This project was created following the tutorial by [Tech With Tim](https://www.youtube.com/watch?v=Oo8-nEuDBkk). Special thanks to Tim for the excellent tutorial and guidance.

## 📝 License
This project is open source and available under the MIT License.
