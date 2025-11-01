🎬 IMDB 50K Movie Review Sentiment Analysis

📖 About

This notebook is my end-to-end sentiment analysis project using the IMDB 50K Movie Reviews dataset.
I built and trained an NLP model that can predict whether a movie review is positive or negative.
Everything — from importing data to evaluating the model — is done inside this one Colab notebook

⚙️ What’s inside the notebook

Data Loading: I used the IMDB dataset with 50 000 labeled reviews.

Data Cleaning: removed HTML tags, punctuation, and stopwords.

Text Pre-processing: tokenization, padding, and converting words to sequences.

EDA (Exploratory Data Analysis): checked the distribution of positive/negative reviews and visualized frequent words using plots.

Model Building:

Used Embedding layer + LSTM for sequence modeling.

Training: trained the model on the cleaned text data.

Evaluation: checked accuracy, confusion matrix, and loss/accuracy curves.

📈 Model Result

Model accuracy: around 84%

The model performs well in distinguishing positive and negative reviews.

💻 How to Run

If you want to try it yourself:

Open the notebook in Google Colab.

Run all cells (dataset is loaded directly or through Keras datasets).

Check the final model predictions at the bottom.
