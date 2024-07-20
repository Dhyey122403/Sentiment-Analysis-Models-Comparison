# Sentiment Analysis of Flipkart Reviews

## Overview
This project focuses on sentiment analysis of Flipkart reviews using a combination of traditional machine learning algorithms and pre-trained NLP transformers. The primary goal is to classify the reviews into positive, neutral, or negative sentiments and compare the performance of different models.

## Data Description
The dataset contains reviews from Flipkart, along with their ratings. The ratings are converted into sentiment labels:
- Ratings 4 and 5: Positive
- Rating 3: Neutral
- Ratings 1 and 2: Negative

## Models and Techniques Used
- Data Cleaning and Preprocessing
- Visualization: Pie Chart, Word Cloud
- Sentiment Analysis using:
  - Pre-trained Transformers (Hugging Face)
  - VADER Sentiment Analysis
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - Naive Bayes
  - Gradient Boosting

## Results
| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | 0.911063 |
| SVM                  | 0.928416 |
| Random Forest        | 0.960954 |
| Naive Bayes          | 0.865510 |
| Gradient Boosting    | 0.932755 |

## Usage
1. Clone the repository.
2. Install the required packages.
3. Run the provided Jupyter Notebook or Python script.

## Installation
```bash
pip install -r requirements.txt
