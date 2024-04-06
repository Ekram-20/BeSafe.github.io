## Project Description
A system that accepts user reports in Arabic and classifies them into one of four categories: car accidents, crime, fire, and robbery. The system uses a trained machine learning model to perform this classification. The system can accept input either as text or as voice recordings.

## Technologies
The project is implemented in Python and uses the following libraries and tools:

- **Streamlit:** for the web interface.
- **SpeechRecognition:** for transcribing audio input.
- **Googletrans:** for translating Arabic text to English.
- **NLTK:** for text preprocessing.
- **Scikit-learn and Joblib:** for machine learning model training and persistence.
- **Sounddevice and Wavio:** for handling audio input.

## Demo
https://github.com/Ekram-20/We-are-safe/assets/77066505/54e354bf-bd1a-4134-abe8-edd0aa9b35f6



## Setup
To set up the project locally, follow these steps:
1. Clone the repository.
2. Install the required Python libraries, which are listed in the `requirements.txt` file.
3. Ensure that you have the trained model and vectorizer files (`kullanaAmn1.pkl` and `vectorizer.pkl`) in the root directory.

## Usage

You can run the system locally by navigating to the root directory of the project in a terminal and running `streamlit run app.py`.

The system presents two options for providing input: via text or voice recording. After providing input, press the "إرسال" button to classify the report. The system will display the classified category.

## Team

This project was developed by a team of dedicated developers:
- [Ekram Fares](https://github.com/Ekram-20)
- [Abdulrahamn Khalid](https://github.com/Abdulrahman0Khaled)
- [Tarek Zain](https://github.com/zain-codes)
- [Shahad Mohammed](https://github.com/Shahad-Mohammed)
