  The News Summarizer application is designed with user convenience in mind, featuring a user-friendly interface built using Python's Tkinter library. The tool accepts both URLs
of online news articles and PDF files containing news content, offering flexibility in input formats. Once an article or document is provided, the application uses the 
newspaper3k library to download and parse the content. The TextBlob library is then employed to perform natural language processing (NLP) tasks, such as tokenization and 
sentiment analysis. The extracted text is summarized, and the sentiment of the content is evaluated to provide insights into the overall tone of the article.
  One of the standout features of the News Summarizer is its ability to save summarized content in PDF format. This functionality is particularly useful for users who wish to 
archive or share concise versions of news articles. The summarization results are displayed directly within the Tkinter interface, allowing users to review the content 
immediately. Additionally, the application provides sentiment analysis results, indicating whether the summarized content is positive, negative, or neutral, which adds a 
valuable dimension to the news consumption experience. Error handling mechanisms are implemented to manage common issues such as network errors, invalid URLs, and unsupported 
PDF formats, ensuring a smooth and reliable user experience.
