# PRODIGY_DS_04 - Sentiment Analysis on Twitter Data

## Objective

The objective of this project is to perform sentiment analysis on Twitter data using Natural Language Processing (NLP). The project analyzes tweet sentiments using the VADER Sentiment Analyzer and compares the predicted sentiments with the original sentiment labels in the dataset.


## Dataset

- Dataset: Twitter Training Dataset
- Columns:
  - ID
  - Entity
  - Sentiment
  - Tweet Text

## Technologies Used

- Python
- Pandas
- NLTK
- VADER Sentiment Analyzer
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. Imported the Twitter dataset.
2. Removed missing tweet data.
3. Preprocessed tweet text by:
   - Converting text to lowercase.
   - Removing mentions, hashtags, URLs, and special characters.
4. Applied the VADER Sentiment Analyzer.
5. Classified tweets into:
   - Positive
   - Neutral
   - Negative
6. Compared VADER predictions with the original sentiment labels.
7. Visualized sentiment distributions using different charts.
8. Analyzed sentiment across different entities.


## Visualizations

### 1. VADER Sentiment Distribution
Displays the number of Positive, Neutral, and Negative tweets predicted by the VADER model.

### 2. Original Sentiment Distribution
Shows the sentiment labels available in the original dataset.

### 3. Entity Distribution
Displays the number of tweets for each entity.

### 4. Sentiment Distribution Per Entity
A stacked bar chart showing Positive, Neutral, and Negative tweets for every entity.


## Results

- Successfully preprocessed Twitter text.
- Applied VADER sentiment analysis.
- Compared predicted sentiments with original dataset labels.
- Visualized sentiment distribution using multiple charts.
- Analyzed sentiment trends across different entities.



## Conclusion

This project demonstrates the application of Natural Language Processing (NLP) for sentiment analysis on social media data. Using the VADER Sentiment Analyzer, tweets were classified into Positive, Neutral, and Negative categories. The visualizations provide valuable insights into public sentiment and how it varies across different entities.


## Skills Demonstrated

- Data Cleaning
- Text Preprocessing
- Natural Language Processing (NLP)
- Sentiment Analysis
- Data Visualization
- Exploratory Data Analysis (EDA)


## Author
Selvarani B

**Internship:** Prodigy InfoTech – Data Science Internship
