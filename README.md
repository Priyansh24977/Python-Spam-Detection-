# Python Spam Detection and Filter

A machine learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Python.

## Features
- Preprocesses SMS messages.
- Converts text into numerical features using TF-IDF.
- Trains a Multinomial Naive Bayes classifier.
- Predicts whether a message is spam or legitimate.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Multinomial Naive Bayes

## Project Files
- `main.py` — Trains the model and performs spam classification.
- `prepare_data.py` — Prepares the dataset.
- `spam.csv` — SMS dataset.
- `requirements.txt` — Required Python libraries.
- `SMSSpamCollection` — SMS message dataset.

## How to Run

1. Clone this repository.
2. Install dependencies:

   `pip install -r requirements.txt`

3. Run the project:

   `python main.py`

## Dataset
The project uses an SMS spam dataset containing messages labeled as spam or ham.

## Purpose
This project demonstrates text preprocessing, feature extraction, and supervised machine learning for spam detection.
