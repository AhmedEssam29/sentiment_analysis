# Google Play Sentiment Analysis

## Project Overview
This project performs sentiment analysis on user reviews from Google Play Store applications. Utilizing Natural Language Processing (NLP) techniques, the analysis aims to evaluate user sentiments towards various apps, providing insights into user experiences and preferences.

## Datasets
The project leverages the following datasets:

1. **Apps Dataset** (`user_reviews.csv`): Contains information about various applications available on Google Play Store.
   - **Columns**:
     - `main`: Name of the application
     - `Translated_Review`: User review text
     - `Sentiment`: Categorized sentiment of the review (Positive, Negative, Neutral)
     - `Sentiment_Polarity`: Numerical score indicating the polarity of the sentiment
     - `Sentiment_Subjectivity`: Numerical score indicating the subjectivity of the sentiment

2. **Additional Datasets**: If applicable, mention any additional datasets used for sentiment scoring or validation.

## Installation
To run this project, ensure you have Python installed, then install the required packages using pip:

```bash
pip install nltk pandas matplotlib seaborn wordcloud
```
## Usage

- **Data Preparation:** Load the datasets and preprocess the data as necessary. Handle missing values and ensure the Translated_Review column is clean and formatted correctly.

- **Sentiment Analysis:** Utilize the VADER sentiment analysis tool from the NLTK library to analyze the sentiments of the reviews.

- **Visualizations:** Generate visualizations to display sentiment distributions and averages. This includes bar plots, box plots, and word clouds to provide insights into the sentiment analysis results.

- **Word Count Analysis:** Analyze the word count of the Translated_Review to identify the most frequently used words and phrases.

## Example Analysis

The analysis performed in this project includes:

- Sentiment Scores: Calculation of average positive, negative, and neutral sentiment scores for the reviews.
- Visualizations:
-- Bar plot showing average sentiment scores.
-- Box plot displaying the distribution of sentiment scores.
-- Word cloud visualizing the most common words found in user reviews.


![alt text](https://github.com/AhmedEssam29/sentiment_analysis/blob/main/22.png?raw=true)
 
