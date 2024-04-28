Email Spam Detection using Machine Learning
This project aims to detect spam emails using machine learning techniques. It utilizes a dataset containing both spam and non-spam (ham) emails to train a classifier, allowing it to distinguish between the two types of emails.

Features:
Data Processing: The project preprocesses the email data by converting it to lowercase, removing punctuation, and filtering out short words to improve the quality of the text data.
Model Training: It employs the Naive Bayes classifier from the scikit-learn library to train a model on the preprocessed email data.
Visualization: The project provides visualizations of data distribution and commonly used words in spam and ham emails using libraries like Matplotlib and Seaborn.
Word Clouds: It generates word clouds to visualize the most frequently occurring words in both spam and ham emails.
Prediction: Users can input their email content, and the trained model will predict whether it is spam or ham.
Usage:
Clone the repository to your local machine.
Ensure you have the necessary dependencies installed, including scikit-learn, NLTK, WordCloud, and Matplotlib.
Run the provided Python script to train the model and visualize the data.
Utilize the trained model to predict whether new email content is spam or ham.
Example:
python
Copy code
# Example usage of the trained model
email_content = "Special offer: Buy now and get 50% off!"
prediction = predict_spam_or_ham(email_content)
print(prediction)  # Output: Spam
Contributors:
Bomma Prashnath
Feel free to contribute, report issues, or suggest improvements!
