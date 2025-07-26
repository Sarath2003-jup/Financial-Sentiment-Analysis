# Financial-Sentiment-Analysis
This project performs sentiment analysis on financial text data using traditional machine learning techniques. The goal is to classify financial sentences or headlines into Positive, Neutral, or Negative sentiments.

🧠 Technologies Used
Python

NLTK for preprocessing (stopwords, stemming)

Scikit-learn for feature extraction (TF-IDF) and model training

Pandas, Seaborn, Matplotlib for data handling and visualization

🗃️ Dataset
The dataset used (finance.csv) contains financial sentences labeled with sentiment. It has the following structure:

Sentence	Sentiment

Sentiments were mapped as:

Neutral → 0

Positive → 1

Negative → 2

🔍 Preprocessing Steps
Text Cleaning: Removed non-alphabetical characters using regex.

Lowercasing: Standardized all text to lowercase.

Tokenization and Stopword Removal: Removed common English stopwords.

Stemming: Reduced words to their root forms using PorterStemmer.

TF-IDF Vectorization: Converted processed text to numerical vectors.

I trained my model on Logistic Regression to get a 81% accuracy on my data
