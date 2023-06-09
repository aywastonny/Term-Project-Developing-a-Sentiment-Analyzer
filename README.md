# Term-Project-Developing-a-Sentiment-Analyzer
# Sentiment Analyzer
This is a sentiment analyzer app that predicts the sentiment of a given review. It uses a support vector machine (SVM) model trained on a dataset of movie reviews.

# Usage
To use this app, simply enter a piece of text (a review) into the provided textbox and click "Submit". The app will then predict the sentiment of the review and display it on the screen.

# Dependencies
This app requires the following dependencies:
gradio
scikit-learn

#How it Works
The model processes the input text by converting it into a vector using a pre-trained vectorizer. The resulting vector is then fed into an SVM model which predicts the sentiment of the text as either positive or negative.

# Installation
To install the required dependencies, you can use the following command:
pip install gradio scikit-learn

# Launching the App
To launch the app, simply run the following command:

python app.py
This will launch the app in your default web browser.


The local version can be accessed at http://127.0.0.1:7863 
The live at https://status.gradio.app.

# About the Author
This app was created by Aywa Stonny. You can find more of my work on my GitHub profile.
