# Financial News Analysis: NVIDIA and Spotify

This project analyzes financial news articles related to **NVIDIA** and **Spotify** using **Natural Language Processing (NLP)** techniques. The dataset contains headlines, summaries, and publication dates, making it ideal for tasks like sentiment analysis, topic modeling, and named entity recognition. The goal is to extract actionable insights, such as identifying negative sentiment, uncovering key topics, and detecting relationships between entities.

---

## **Project Overview**

### **Key Steps**
1. **Data Exploration**: Understand the dataset's structure, content, and distribution.
2. **Text Preprocessing**: Clean and prepare the text data for analysis.
3. **Topic Modeling**: Identify common themes or topics in the financial news articles.
4. **Named Entity Recognition (NER)**: Extract key entities (e.g., companies, individuals, locations) from the text.
5. **Keyword Extraction**: Identify the most important words in the dataset.
6. **Sentiment Analysis**: Analyze the sentiment of the financial news articles.
7. **Final Report**: Summarize the findings and provide actionable recommendations.

---

## **Technologies Used**
- **Python**: Primary programming language.
- **Libraries**:
  - `pandas` and `numpy` for data manipulation.
  - `nltk` and `spaCy` for NLP tasks.
  - `scikit-learn` for topic modeling and TF-IDF.
  - `matplotlib` and `seaborn` for data visualization.
  - `wordcloud` for visualizing keywords.

---

## **Dataset**
The dataset used in this project is the **Financial News Dataset: NVIDIA and Spotify**, sourced from [Kaggle](https://www.kaggle.com/dataset/nvidia-spotify-financial-news). It contains the following columns:
- `Company`: The company to which the news article pertains (NVIDIA or Spotify).
- `Headline`: The title or headline of the news article.
- `Summary`: A brief excerpt or summary of the news article.
- `Date`: The publication date of the news article.

---

## **Code Structure**
The project is organized into the following steps:
1. **Data Exploration**: Load and inspect the dataset.
2. **Text Preprocessing**: Clean and preprocess the text data.
3. **Topic Modeling**: Apply Latent Dirichlet Allocation (LDA) to identify topics.
4. **Named Entity Recognition (NER)**: Extract and analyze key entities.
5. **Keyword Extraction**: Use TF-IDF to identify important keywords.
6. **Sentiment Analysis**: Analyze the sentiment of the articles.
7. **Final Report**: Summarize the findings and provide recommendations.

---

## **Bilingual Capabilities**
This project showcases my **polyglot skills** by handling a **multilingual dataset** containing both **Portuguese** and **English** text. Here’s how I tackled the challenge:
1. **Language Detection**: Used libraries like `langdetect` to identify the language of each text snippet.
2. **Translation**: Translated Portuguese text to English using the `googletrans` library for consistent analysis.
3. **Bilingual Preprocessing**: Applied text preprocessing techniques (e.g., stopword removal, stemming) to both languages, ensuring accurate and meaningful results.
4. **Bilingual Reporting**: Provided insights and visualizations in both **English** and **Portuguese** to make the analysis accessible to a wider audience.

---

## **How to Run the Code**
1. Clone the repository:
   ```bash
   git clone https://github.com/mahlodi-makobe/financial-news-analysis.git
