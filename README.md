# Extraction-and-Analysis-of-Text
The objective is to analyze text content from a list of URLs. This involves extracting article titles and text, then performing natural language processing to generate metrics like sentiment, readability, and word usage. Finally, the results are stored for further analysis or visualization.

The process involves the following steps:

1. __URL Extraction:__ Iterate through a list of URLs stored in a CSV file.

2. __Text Extraction:__ Extract the article title and text content from each URL using web scraping techniques. To extract article's text and title from the given url in Input.csv, I used "beautiful soup" library of python which help in extracting text from url effortlessly.

3. __Text Analysis:__ Analyze the extracted text using natural language processing (NLP) techniques to derive various metrics such as sentiment scores, readability scores, and word usage statistics. To analyze the text extracted from the url, I made a function "analyze_text". This function will do the analysis part and give positive score, negative score, polarity, subjectivity, average sentence length, complex word percent, fog index, average number of words per sentence, complex word count, word count, syllable per word, personal pronouns, average word length. 
	For the analysis part, I used "NLTK" library which used in NLP.

4. __Data Storage:__ Store the analysis results along with other relevant information (such as URL, article title, and word count) into a CSV file for further analysis or visualization.

By performing these steps, the code aims to provide insights into the content of the articles, allowing for deeper understanding and analysis of the text data sourced from the provided URLs.
