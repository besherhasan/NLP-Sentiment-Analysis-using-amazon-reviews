# NLP-Sentiment-Analysis-using-amazon-reviews
# Sentiment Analysis using Amazon Reviews

This project focuses on sentiment analysis using Amazon product reviews. It explores two different techniques: VADER (Valence Aware Dictionary and Sentiment Reasoner) and the Roberta Pretrained Model from the Transformers library.

## Getting Started

### Prerequisites

- Python
- Jupyter Notebook
- Transformers library
- NLTK
- Pandas
- Matplotlib
- Seaborn


## The images below shows the testing of the models

![Testing Another Model](./Testing%20another%20model.png)
![Testing the Model](./Testing%20the%20model.png)


Install the required dependencies using the `requirements.txt` file.

```bash
pip install -r requirements.txt

Data
The project uses the Amazon product reviews dataset, which can be found at Amazon Customer Reviews (a.k.a. Product Reviews) on AWS.

Project Overview
Data Preprocessing: The project starts by importing the necessary libraries and reading in the Amazon product reviews data using Pandas.

Exploratory Data Analysis: It begins with some exploratory data analysis, including visualizations of the review scores and their distribution.

VADER Sentiment Analysis: The project performs sentiment analysis using the VADER library, which provides negative, neutral, positive, and compound scores for each review.

Roberta Pretrained Model: The Roberta Pretrained Model from the Transformers library is used for sentiment analysis. This model provides sentiment scores for negative, neutral, and positive sentiments.

Comparison of Results: The project compares the sentiment analysis results between VADER and the Roberta model and visualizes the differences.

Review Examples: The project provides examples of reviews where the model scores and review scores differ significantly.

Usage
You can run the project in a Jupyter Notebook environment. Follow the code in the notebook to understand the sentiment analysis process using both VADER and the Roberta Pretrained Model.

Transformers Pipeline
To make sentiment predictions using the Transformers library, a pipeline is set up for quick and easy sentiment analysis without manually configuring models. Example predictions using this pipeline are provided in the notebook.




