# sentiment_analysis_nltk_roberta

## Description:

This GitHub repository contains a Python project for conducting sentiment analysis on Amazon product reviews. The project utilizes various natural language processing (NLP) techniques, machine learning models, and data visualization to gain insights into customer sentiments.

## Key Components:

- Data Processing and Visualization: The project begins by loading and processing a dataset of Amazon product reviews. It includes data cleaning and visualization using Pandas, Matplotlib, Seaborn, and NLTK libraries. The 
  initial visualization presents a bar chart displaying the distribution of review scores.

- Sentiment Analysis with NLTK: NLTK is used for tokenization, part-of-speech tagging, and named entity recognition (NER) to analyze the textual content of reviews. The sentiment intensity of each review is determined 
  using NLTK's VADER sentiment analysis tool.

- Sentiment Analysis with RoBERTa: The project employs the Cardiff NLP's Twitter RoBERTa model to perform sentiment analysis on the reviews. It uses the Hugging Face Transformers library for model loading and inference.

- Combining Results: Sentiment scores from both NLTK and RoBERTa are combined into a single DataFrame for further analysis.

- Data Visualization: Data visualization is a significant aspect of this project. It includes pair plots that visualize the relationships between sentiment scores and review scores. These visualizations provide insights 
  into how different sentiment analysis methods correlate with the actual review scores.

## Acknowledgments:

* The project uses the NLTK and Hugging Face Transformers libraries for NLP and machine learning tasks.
* The sentiment analysis models employed in this project are based on publicly available resources from Cardiff NLP and the NLTK library.
