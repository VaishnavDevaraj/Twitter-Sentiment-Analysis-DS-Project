Twitter Sentiment Analysis

Description

This project performs Sentiment Analysis on Twitter data, classifying tweets into positive and negative sentiments. By applying machine learning techniques to Twitter data, this project aims to help understand public opinion trends, identify sentiment dynamics, and support data-driven decision-making in areas like marketing, politics, and social media analysis.


Installation:-

1. Clone this repository:

git clone <repository-url>


2. Install the required libraries:

pip install -r requirements.txt


3. Download the dataset: Make sure the Twitter sentiment dataset (e.g., training.1600000.processed.noemoticon.csv) is in the same directory as the main script or notebook.



Usage:-

1. Data Loading: Open the Jupyter Notebook and run the first cells to load and preview the dataset.


2. Data Preprocessing: Follow the notebook instructions to preprocess the text data (tokenization, lemmatization).


3. Feature Extraction: Run the cells to transform text data into numerical format using TfidfVectorizer.


4. Model Training: Train models like Support Vector Machine, Naive Bayes, and Logistic Regression.


5. Evaluation: Evaluate models using confusion matrix, accuracy, precision, and recall scores.



Example:-

After setting up and running the notebook, the program will output results similar to:

Support Vector Classifier Accuracy: 83%
Logistic Regression Accuracy: 81%
Naive Bayes Accuracy: 79%

The confusion matrix and classification report will provide additional details on each model's performance.

Features:-

Data Preprocessing: Uses nltk to clean and prepare the dataset for machine learning models.

Feature Extraction: Converts text data into numerical format with TfidfVectorizer.

Model Training: Includes models such as SVC, Naive Bayes, and Logistic Regression for classification.

Evaluation: Evaluates model performance with metrics like accuracy, precision, recall, and F1 score.


Contribution:-

Contributions to this project are welcome! Here’s how you can get involved:

1. Contact: Reach out via GitHub Issues or start a discussion in the repository for any questions.


2. Specs and Unit Tests: Write unit tests to ensure that new code works as expected. Include these in a tests folder.


3. Documentation: Please provide clear and concise documentation in code comments and update this README if necessary.



How to Contribute:-

Fork the repository and create a new branch.

Make changes and ensure tests pass.

Submit a pull request describing your changes and the problem it solves.

Dataset Used:-

The dataset provided is the Sentiment140 Dataset which consists of 1,600,000 tweets that have been extracted using the Twitter API. The various columns present in this Twitter data are:
>target: the polarity of the tweet (positive or negative)
>ids: Unique id of the tweet
>date: the date of the tweet
>flag: It refers to the query. If no such query exists, then it is NO QUERY.
>user: It refers to the name of the user that tweeted
>text: It refers to the text of the tweet
***Note: The Sentiment140 Dataset is available on Kaggle.
