
# Web Scraping Chatbot

This project is a **web scraping chatbot** that uses **Selenium** for web scraping, **BeautifulSoup** for HTML parsing, and **Gemini AI** for analyzing content. The chatbot can scrape text data from web pages, extract all links, and generate responses based on the scraped content.

## Features
- **Web scraping**: Extracts text content from web pages.
- **Link traversal**: Scrapes all links and their corresponding content on a given webpage.
- **AI analysis**: Uses Gemini AI for analyzing scraped content.
- **Interactive chatbot**: Allows users to query the scraped data.

---

## Installation

Follow these steps to set up and run the project:

### Prerequisites
- Python 3.7 or higher
- [Google Gemini API Key](https://developers.generativeai.google/) (Sign up for an API key)
- [ChromeDriver](https://sites.google.com/chromium.org/driver/) installed

### Libraries Used
Install the required Python libraries:
```bash
pip install selenium
pip install webdriver-manager
pip install beautifulsoup4
pip install google-generativeai
```

---

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/NiteshAnand190/Web-Scrapping-Chatbot.git
   cd Web-Scrapping-Chatbot
   ```

2. **Set up API Key**:
   - Replace `api_key = ""` in the script with your Google Gemini API Key.

3. **Run the Script**:
   ```bash
   python <script_name>.py
   ```

4. **Provide Input**:
   - Enter the URL of the website you want to scrape.
   - Use the chatbot interface to ask questions based on scraped content.

---

## Project Structure
```
Web-Scrapping-Chatbot/
├── main_script.py        # Main Python script
├── README.md             # Project documentation
└── requirements.txt      # Required Python libraries
```

---

## How It Works

1. **Web Scraping**: The Selenium WebDriver navigates to a given URL, and BeautifulSoup extracts content.
2. **AI Analysis**: Scraped data is sent to Gemini AI, which generates meaningful insights or answers queries.
3. **Chatbot Interface**: Users can interact with the chatbot for querying scraped content.

---

## Example
- **URL**: `https://example.com`
- **Output**: Extracted plain text, analyzed AI responses, and interaction via the chatbot interface.

---

## Contributing
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---
