# Sentiment-Analysis-and-Topic-Modeling-of-News-Articles

This project employs Natural Language Processing (NLP) to analyze key topics and sentiments in media coverage of the Central Vista Project. It systematically processes and evaluates 1157 news articles to identify prevalent narratives and sentiment trends, providing valuable insights into public and media perception.

## Objective

The aim of this project is to develop an NLP model capable of identifying critical topics and assessing sentiments within media coverage concerning the Central Vista Project.

## Approach

- **Data Collection**: Scraped 1157 articles using Beautiful Soup, Newspaper3k, Google Search Console API, and Selenium.
- **Data Preprocessing**: Employed techniques such as stopword removal, lemmatization, tokenization, and n-gram generation with Gensim Phraser.
- **Topic Modeling**:
  - Created a document-term matrix and trained a Latent Dirichlet Allocation (LDA) model, achieving a coherence score of 0.51 across 7 topics.
  - Employed BERTopic for comparative topic modeling to capture detailed narrative structures.
- **Sentiment Analysis**:
  - Used HuggingFace’s pre-trained models alongside custom functions to analyze topic-wise sentiment trends across a 48-month period.

## Results

- **Efficiency Gains**: Automated pipeline saved over 50 hours of manual analysis and reduced data processing time by 99.7% with a runtime of under 9 minutes.
- **Topic Insights**: Identified 7 major topics using both LDA and BERTopic, covering all significant events and developments related to the Central Vista.
- **Sentiment Trends**: Analyzed sentiments showed 58.1% of the coverage as positive and 41.9% as negative, highlighting a predominantly positive media outlook with substantial critiques.

## Contributors
1. <a href="https://github.com/ASTITVAXX">@astitva</a>
2. <a href="https://github.com/srishas22">@srisha</a>
