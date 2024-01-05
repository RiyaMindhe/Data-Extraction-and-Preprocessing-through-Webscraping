# Data-Extraction-and-Preprocessing-through-Webscraping-Past

Web scraping emerges as a vital tool in this context, enabling us to swiftly harvest pertinent data from platforms like social media, academic journals, or editorial columns. Once extracted, this data becomes a rich resource for sentiment analysis, aggregating diverse opinions about a product or individual, and offering a consolidated view of prevailing sentiments.

Step 1: Fetching Raw HTML Content from the Web
We’ll be using Python’s inbuilt library urllib and the inbuilt functions urlopen to extract the raw content from the url: https://quotes.toscrape.com/

Step 2:
Understanding Regular Expression
Regular expressions (regex) are powerful tools for text pattern matching and extraction. In the domain of NLP, they play a crucial role in various pre-processing and information retrieval tasks. Here is a brief summary of what they can do:

Text Cleaning  
Regex can be used to clean up text data, removing unwanted characters, URLs, tags, or any other non-essential elements.

Phrase Extraction  
Regex can be used to extract specific phrases or patterns from the text, such as email addresses, phone numbers, or any domain-specific entities.

Text Replacement  
In tasks where certain patterns within the text need to be substituted or normalized, regex provides a robust way to achieve this.

Tokenization  
Regex can also be used in defining patterns to split text into words and tokens.

Step 3:
Webscraping with BeautifulSoup
BeautifulSoup is a Python package that extracts data from HTML (and XML documents) for web scraping. It contains methods for navigating, finding, and changing parsed tree structures, making it simple to extract data from web pages.

Working with BeautifulSoup allows developers to focus on the data they need rather than the technical mechanics of HTML parsing.
Our goal is to retrieve all the quotes from a designated quotes website. To achieve this, we require the tags encapsulating the text and their respective class names.

You can source these details directly from the raw HTML tags via the developer console, or by visualizing the structured HTML in the Jupyter notebook using soup.prettify().


![image](https://github.com/RiyaMindhe/Data-Extraction-and-Preprocessing-through-Webscraping/assets/84629433/91cf2dfd-e09a-4f83-8d6f-2039e6cf7f1d)

