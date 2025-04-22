**Toxic Comment Classification**
This project is a Machine Learning web app that classifies user-submitted text as toxic or non-toxic, using a deep learning model built with TensorFlow and deployed with an interactive Gradio interface.

**🚀 Features**
Classifies text as different labels of toxic

Built using a deep learning model trained on the Jigsaw Toxic Comment Classification dataset

Fast and responsive web interface powered by Gradio

Clean and easy-to-use UI for real-time testing

Screenshots:
![image](https://github.com/user-attachments/assets/41ae27a3-c864-4bd0-83bc-888c81527cf4)
![image](https://github.com/user-attachments/assets/6431cb6b-6c0c-4fdc-b499-4cece327da3e)



**Tech Stack**
Python 3.12

TensorFlow – for building and training the neural network

Gradio – for creating the web interface

Pandas & NumPy – for data handling

Scikit-learn – for data preprocessing and evaluation

**Dataset**
The model is trained on the Jigsaw Toxic Comment Classification Challenge dataset from Kaggle, which contains over 150k comments labeled as:

toxic

severe_toxic

obscene

threat

insult

identity_hate
**How It Works**
User submits a text comment via the Gradio interface.

The input is preprocessed using standard NLP techniques (lowercasing, punctuation removal, tokenization).

The cleaned text is passed into the TensorFlow model.

The model outputs different labels of toxic
