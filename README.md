# WhatsApp Chat Analysis

## Introduction
This repository contains code for analyzing WhatsApp chat data and conducting sentiment analysis to gain insights into the sentiment of the conversation.

## Project Overview
The project involves loading the WhatsApp chat data, preprocessing the text data, performing sentiment analysis using the VADER Sentiment Intensity Analyzer, and visualizing the results.

## Project Structure
- `Whatsapp_Chat_Analysis.ipynb`: Main Jupyter Notebook containing the code for data analysis and visualization.
- `whatsapp_chat_with_sentiment.csv`: Processed chat data with sentiment analysis results.
- `workcloud.png`: Word clouds png of the data

## Data Processing
I processed the WhatsApp chat data by splitting the lines into timestamp, sender, and message, and then preprocessing the text data to remove punctuation and stopwords.

## Sentiment Analysis
I utilized the VADER Sentiment Intensity Analyzer to assign sentiment scores to each message in the chat data.

## Visualization
I visualized the chat data using word clouds to visualize word frequency and plotted sentiment analysis trends over time.

## Results and Insights
The analysis revealed insights into the most frequent words used in the chat, the overall sentiment of the conversation, and trends observed in sentiment over time.

## Conclusion
This project demonstrates the process of analyzing WhatsApp chat data and conducting sentiment analysis to gain insights into the sentiment of the conversation. Users are encouraged to explore the repository and provide feedback or contributions.

## Usage and Requirements
To run the code, you need Jupyter Notebook and the following Python libraries: pandas, nltk, wordcloud. Simply open the `Whatsapp_Chat_Analysis.ipynb` notebook and follow the instructions.

## License and Acknowledgments
This project is distributed under the MIT License. We acknowledge the use of the VADER Sentiment Intensity Analyzer and other external libraries.
