# Duplicate Question Pair Detection

## Overview

This project tackles the challenge of detecting duplicate questions on Quora, organized by Kaggle. The primary goal is to identify whether two questions have the same meaning, thereby helping to reduce redundant content on the platform. By employing a combination of natural language processing (NLP) techniques and machine learning algorithms, the model achieves an accuracy of approximately 80%.


## Table of Contents

- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Features](#features)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK / spaCy
- Streamlit

## Dataset

The dataset used for this project is sourced from Kaggle, containing pairs of questions and labels indicating whether they are duplicates. You can access the dataset [here](https://www.kaggle.com/c/quora-question-pairs/data).

## Features

- **Natural Language Processing:** Tokenization, stemming, and lemmatization to preprocess text data.
- **Machine Learning:** Various models tested for optimal performance in detecting duplicates.
- **Interactive Web App:** Users can input question pairs and get real-time feedback on their similarity.

## Model

The project utilizes a variety of machine learning techniques, including:
- **TF-IDF Vectorization:** To convert text data into numerical format.
- **Logistic Regression:** As the baseline model for comparison.
- **Random Forest and XGBoost:** Advanced models to improve accuracy.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/prafull904434/Detection-of-Duplication-of-Question-Pair
   ```
2. Navigate to the project directory:
   ```bash
   cd duplicate-question-pair-detection
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To start the Streamlit application, run the following command in your terminal:
```bash
streamlit run app.py
```
This will open a new tab in your web browser with the application interface, where you can input question pairs for duplicate detection.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request.
