# Bird Species Classification

This project is a web application for bird species classification using machine learning models. It allows users to upload bird sound recordings and get predictions on the species of the bird.

## Introduction

This web application is built using Flask, TensorFlow, and librosa. It leverages a pre-trained machine learning model to classify bird species based on their sound recordings. Users can upload audio files, and the application provides real-time predictions on the bird species detected in the recordings.

## Features

- Upload bird sound recordings for species classification
- Real-time prediction of bird species
- User-friendly interface

## Installation

To run this application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your_username/bird-species-classification.git`
2. Navigate to the project directory: `cd bird-species-classification`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Download the dataset and place it in the project directory.
5. Download the pre-trained machine learning model (`Model1.h5`) and the extracted feature dataframe (`extracted_df.pkl`) and place them in the project directory.
6. Run the Flask application: `python app.py`
7. Access the web application in your browser at `http://localhost:5000`.

## Usage

1. Open the web application in your browser.
2. Click on the "Choose File" button to upload a bird sound recording for species classification.
3. Once the upload is complete, click on the "Submit" button.
4. Wait for the prediction to be displayed on the screen.
5. Explore other features of the web application as needed.

## License

This project is licensed under the [MIT License](LICENSE).
