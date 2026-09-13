# SMS Spam Classifier

An end-to-end SMS spam classification project using Natural Language Processing (NLP) and Machine Learning. The project classifies SMS messages as either **Spam** or **Not Spam (Ham)** and includes an interactive Streamlit web application for real-time prediction.

## Project Overview

SMS spam messages are unwanted messages that may contain advertisements, scams, or fraudulent content. This project uses Natural Language Processing and Machine Learning techniques to automatically identify whether a given SMS message is spam.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Natural Language Processing (NLP)
- Text tokenization and preprocessing
- TF-IDF text vectorization
- Machine Learning classification
- Spam/Ham prediction
- Interactive Streamlit web application
- Real-time SMS classification

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit
- Jupyter Notebook

## Project Workflow

**SMS Dataset → Data Cleaning → EDA → Text Preprocessing → TF-IDF Vectorization → Machine Learning Model → Model Evaluation → Streamlit Web Application → Spam/Ham Prediction**

## Project Files

| File | Description |
|---|---|
| `sms-spam-detection.ipynb` | Jupyter Notebook containing data analysis, preprocessing, model training and evaluation |
| `app.py` | Streamlit application for the web interface and SMS prediction |
| `model.pkl` | Trained machine learning model |
| `vectorizer.pkl` | Saved text vectorizer |
| `spam.csv` | SMS spam dataset |
| `requirements.txt` | Python dependencies required to run the project |

## How to Run

### 1. Clone the repository

`git clone https://github.com/Aakash-Dabas/sms-spam-classifier.git`

### 2. Install the required libraries

`pip install -r requirements.txt`

### 3. Run the Streamlit application

`streamlit run app.py`

### 4. Open the application

After running the command, Streamlit will provide a local URL. Open the URL in your web browser to use the SMS Spam Classifier.

## Example

Enter an SMS message into the application and the model predicts whether the message is:

- **Spam**
- **Not Spam (Ham)**

## Author

**Aakash Dabas**

B.Tech Student | Aspiring Data Analyst & Data Scientist
