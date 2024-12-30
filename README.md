# Twitter-Sentiment-Analysis-using-ML
#Shravani Shinde

The goal of this project is to perform sentiment analysis on a dataset imported from Kaggle, which contains 1.6 million tweets labelled as positive or negative. The aim is to provide insights into public sentiments expressed on Twitter.

Overview:
- Cleaning and preprocessing the raw data tweets
- Converting the textual data into  numerical form
- Building a Logistic Regression model for binary sentiment classification
- Evaluating the model performance and saving it for future use

Dataset: 
Sentiment140 dataset containing 1.6 million tweets, each lablled as-
0= Positive tweet
1= Negative tweet (converted from original 4)

Workflow:
1. Preprocessing: Removing non alphabetic characters, stopwords, lowercase texts. Applying stemming to reduce words to their root word.
2. Data splitting: Splitting the data into Trainig(80%) and Testing(20%) sets.
3. Feature Extraction: Converting the textual data into numerical form using TF-IDF Vectorization.
4. Model Training: Training the Logistic Regression model on the preprocessed data.
5. Evaluation: Training accuracy= 92.68% , testing accuracy= 63.10%.
6. Model Saving: Saving the model using pickel for future deployment and use.

Python Libraries Used: nltk, scikit-learn, pandas, numpy, pickle.
