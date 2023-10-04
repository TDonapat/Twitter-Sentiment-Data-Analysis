# Twitter Sentiment Data Analysis


Welcome to the Twitter Sentiment Data Analysis project repository! This project aims to analyze sentiments expressed in tweets sourced from Kaggle, with a dataset containing 27,480 tweets. The dataset encompasses diverse attributes such as TextID, Text, Selected_text, Sentiment, Time of Tweet, Age of user, Country, Population of the country, Land area, and Density.

### Introduction

Twitter, with approximately 450 million monthly active users as of 2023, is a significant platform for sharing thoughts and ideas within 280 characters. This project delves into Natural Language Processing (NLP) techniques, specifically sentiment analysis, to extract subjective information from tweets. Understanding public sentiment is vital for political analysis, public opinion research, and various fields where grasping people's thoughts and emotions is crucial.

### Preprocessing

To ensure accurate sentiment analysis, the dataset underwent several preprocessing steps:

- **URL Removal:** Regular expressions were used to eliminate URLs from tweets, replacing them with blank spaces.
  
- **Tokenization:** NLTK library packages, including word_tokenize, were utilized for word tokenization.
  
- **Stopword Removal:** Stopwords, punctuation, and special characters were removed to focus on meaningful content.
  
- **Lemmatization:** NLTK WordNetLemmatizer was employed for lemmatization, ensuring accurate transformation of words.

The ultimate goal was to transform textual data into numerical feature vectors using Bag of Words and TF-IDF Vectorization strategies.

### Repository Structure

The repository is organized as follows:

- **Code:** This folder contains a Jupyter Notebook (.ipynb) and an HTML version of the code for the sentiment analysis and visualization project.
  
- **Data:** Here, you'll find the dataset files:
  - `train.csv`: The training dataset for model development.
  - `test.csv`: The testing dataset for model evaluation.

### Getting Started

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/TDonapat/Twitter-Sentiment-Data-Analysis.git
   ```

2. Navigate to the `code` folder and open the Jupyter Notebook to explore the code and analysis.

3. Dataset files are available in the `data` folder for reference and analysis.

### Dependencies

Ensure you have the following libraries installed:

- Python 3.x
- Jupyter Notebook
- NLTK
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

**Disclaimer:** This project is intended for educational and research purposes only. The sentiments expressed in the dataset do not reflect the views of the repository owner.

Feel free to explore, modify, or enhance the code and analysis according to your specific requirements. If you have any questions or need further assistance, please don't hesitate to reach out!

---
