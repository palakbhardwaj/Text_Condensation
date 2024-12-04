# Text_Condensation
A Python script that scrapes, processes, and summarizes Wikipedia articles using web scraping and NLP techniques.


This project demonstrates a web scraping and text summarization workflow using Python. It scrapes content from a Wikipedia article on **Natural Language Processing (NLP)**, processes the text, and generates a summary of the key information.

## Features
- **Web Scraping**: Uses `urllib` and `BeautifulSoup` to fetch and parse Wikipedia content.
- **Text Preprocessing**: Removes unnecessary characters, punctuation, and stopwords from the text.
- **Tokenization**: Splits text into sentences and words using NLTK.
- **Word Frequency Analysis**: Calculates word frequencies to identify the most important terms.
- **Text Summarization**: Generates a concise summary of the article using sentence scoring and ranking.

## Setup Instructions

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/nlp-wikipedia-scraper.git
   cd nlp-wikipedia-scraper
   ```

2. **Install dependencies**:
   ```bash
   pip install beautifulsoup4 nltk matplotlib
   ```

3. **Download NLTK resources**:
   The script requires additional NLTK resources. Run the following commands in Python:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```

4. **Run the script**:
   ```bash
   python scraper_and_summarizer.py
   ```

## File Structure
- **scraper_and_summarizer.py**: Main script that performs web scraping, preprocessing, and summarization.
- **README.md**: Documentation for the project.
- **requirements.txt**: List of dependencies for easy installation.

## Output
- **Text Summary**: A concise summary of the scraped article, displayed in the terminal.
- **Word Frequency Plot**: A bar plot visualizing the top 30 most frequent words.

## Key Libraries Used
- `BeautifulSoup`: HTML and XML parsing.
- `urllib`: HTTP requests for web scraping.
- `NLTK`: Natural Language Toolkit for text processing.
- `matplotlib`: Visualization of word frequencies.
- `re`: Regular expressions for text cleaning.

## Example Summary
After running the script, a summary of the article on **Natural Language Processing** is displayed, highlighting the most important points in the text.

## Future Enhancements
- Add error handling for network issues or invalid URLs.
- Extend summarization to include user-defined word or sentence limits.
- Save the summary and word frequency plot to a file.


