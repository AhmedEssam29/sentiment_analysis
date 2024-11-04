# Google Play Sentiment Analysis

## Project Overview
This project performs sentiment analysis on user reviews from Google Play Store applications. Utilizing Natural Language Processing (NLP) techniques, the analysis aims to evaluate user sentiments towards various apps, providing insights into user experiences and preferences.

## Datasets
The project leverages the following datasets:

1. **Apps Dataset** (`apps.csv`): Contains information about various applications available on Google Play Store.
   - **Columns**:
     - `App`: Name of the application
     - `Translated_Review`: User review text
     - `Sentiment`: Categorized sentiment of the review (Positive, Negative, Neutral)
     - `Sentiment_Polarity`: Numerical score indicating the polarity of the sentiment
     - `Sentiment_Subjectivity`: Numerical score indicating the subjectivity of the sentiment

2. **Additional Datasets**: If applicable, mention any additional datasets used for sentiment scoring or validation.

## Installation
To run this project, ensure you have Python installed, then install the required packages using pip:

```bash
pip install nltk pandas matplotlib seaborn wordcloud
