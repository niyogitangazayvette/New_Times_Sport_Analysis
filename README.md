In this project, I worked as a junior data analyst tasked with uncovering insights from sports news published on The New Times Rwanda website. The goal was to extract, clean, and analyze articles from the sports section to understand trending topics in Rwandan sports journalism.

Workflow Overview:

Part 1: Data Scraping
I sent a GET request to the sports section of the website and used BeautifulSoup to parse the HTML. I extracted all article links containing the word “sports”, and stored them in a list. Then, I looped through each link, scraped the visible text, and collected the raw content from each article.

Part 2: Text Cleaning & Preprocessing
The raw text was cleaned by removing non-alphanumeric characters, punctuation, single characters, and extra spaces. All text was converted to lowercase. I stored this cleaned text in a separate DataFrame alongside the original content for comparison.

Part 3: Text Analysis & Visualization
I analyzed the cleaned data by generating a word cloud of the most frequent words, performing a frequency distribution of the top 20 terms, and identifying common bigrams/trigrams to see what sports topics dominate the media.
