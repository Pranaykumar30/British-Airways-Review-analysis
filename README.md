Sentiment Analysis of British Airways Airline Reviews**

---

**Overview:**

This Jupyter Notebook presents an in-depth analysis of sentiment expressed in British Airways (BA) airline reviews. By leveraging natural language processing (NLP) techniques and machine learning models, the analysis aims to provide actionable insights for enhancing service quality and customer satisfaction.

---

**Contents:**

1. **Data Loading:** 
   - The notebook begins by loading the dataset containing BA airline reviews from a CSV file.

2. **Exploratory Data Analysis (EDA) & Pre-processing:** 
   - Exploratory data analysis is performed to understand the structure and distributions of the data.
   - Necessary pre-processing steps are conducted, including handling missing values, selecting relevant columns, and merging text fields.

3. **Data Cleaning:** 
   - Text data undergoes cleaning processes to remove unnecessary characters, URLs, emojis, and stopwords.
   - Lemmatization is performed to reduce words to their base forms.

4. **Word Cloud Visualization:** 
   - A word cloud visualization is generated to illustrate the most frequent words from the reviews in the dataset.

5. **Sentiment Analysis:** 
   - Sentiment analysis is conducted using the NLTK library's SentimentIntensityAnalyzer.
   - The sentiment scores (compound, negative, neutral, positive) are calculated for each review.

6. **Classification:** 
   - A classification model is built using a Multinomial Naive Bayes classifier to predict sentiment labels (positive, negative, neutral) based on TF-IDF vectorized text data.
   - The model is trained, evaluated, and performance metrics such as precision, recall, and F1-score are calculated.

---

**Requirements:**

- Python 3.x
- Jupyter Notebook
- Libraries: numpy, pandas, matplotlib, nltk, wordcloud, spacy, sklearn

---

**Usage:**

1. Ensure that Python and Jupyter Notebook are installed on your system.
2. Install the required libraries by running `pip install numpy pandas matplotlib nltk wordcloud spacy scikit-learn`.
3. Download the provided CSV file containing the BA airline reviews dataset.
4. Open the Jupyter Notebook and run each cell sequentially to execute the code and perform the analysis.
5. Review the results, visualizations, and insights generated from the analysis.

---

**Visualizations:**

- The notebook includes various visualizations such as bar plots, histograms, and word clouds to illustrate key findings and trends in the data.
- ![output](https://github.com/Pranaykumar30/British-Airways-Review-analysis/assets/141347187/9bb3b879-529d-441a-876e-542e898ebb3c)
- ![image](https://github.com/Pranaykumar30/British-Airways-Review-analysis/assets/141347187/bcb3effd-3787-44eb-aac3-0240980e25ee)
- ![image](https://github.com/Pranaykumar30/British-Airways-Review-analysis/assets/141347187/38a8b0aa-6a70-403c-8034-37ab50441fb7)
- ![image](https://github.com/Pranaykumar30/British-Airways-Review-analysis/assets/141347187/697bd691-d652-4098-8355-57ac12ab4455)





---

**Author:**

YELLANURU MADASI PRANAY KUMAR

---

**License:**

This project is licensed under the [Your License] License - see the [LICENSE.md](link) file for details.

---
