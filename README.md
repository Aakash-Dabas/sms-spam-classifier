# SMS Spam Classifier

An end-to-end SMS spam classification project using Natural Language Processing (NLP) and Machine Learning. The project classifies SMS messages as either **Spam** or **Not Spam (Ham)** and includes a web application for real-time prediction.

## Project Overview

SMS spam messages are unwanted messages that may contain advertisements, scams, or fraudulent content. This project uses machine learning and NLP techniques to automatically identify whether a given SMS message is spam.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Natural Language Processing (NLP)
- Text vectorization using TF-IDF
- Machine Learning classification
- Spam/Ham prediction
- Flask web application
- Real-time SMS classification

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Flask
- Jupyter Notebook

## Project Workflow

**SMS Dataset → Data Cleaning → EDA → Text Preprocessing → TF-IDF Vectorization → Machine Learning Model → Model Evaluation → Flask Web Application → Spam/Ham Prediction**

## Project Files

| File | Description |
|---|---|
| `sms-spam-detection.ipynb` | Jupyter Notebook containing data analysis, preprocessing, model training and evaluation |
| `app.py` | Flask application for the web interface |
| `model.pkl` | Trained machine learning model |
| `vectorizer.pkl` | Saved text vectorizer |
| `spam.csv` | SMS spam dataset |
| `requirements.txt` | Python dependencies required to run the project |

## How to Run

1. Clone this repository.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Run the Flask application using `python app.py`.
4. Open the local URL displayed in the terminal in your web browser.

## Example

Enter an SMS message into the application and the model predicts whether the message is:

- **Spam**
- **Not Spam (Ham)**

## Author

**Aakash Dabas**

B.Tech Student | Aspiring Data Analyst & Data Scientist
