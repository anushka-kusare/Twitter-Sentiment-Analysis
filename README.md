# Twitter Sentiment Analysis Using NLP and Orange Data Mining

## Project Overview

This project focuses on analysing Twitter data and classifying tweets into Positive, Negative and Neutral sentiments using Natural Language Processing (NLP) and Machine Learning techniques.

The project was implemented using Orange Data Mining through a visual workflow.

## Dataset

- Original dataset: Approximately 27,481 tweets.
- Sample used for analysis: 5,000 tweets.
- Target variable: Sentiment.
- Sentiment categories: Positive, Negative and Neutral.

## Tools and Technologies

- Orange Data Mining
- Natural Language Processing (NLP)
- Text Preprocessing
- Bag of Words
- Naive Bayes Classification
- Cross-Validation

## Project Workflow

1. **File:** Imported the Twitter dataset.
2. **Data Sampler:** Selected a sample of 5,000 tweets for analysis.
3. **Corpus:** Converted raw tweet text into an NLP-readable corpus.
4. **Preprocess Text:** Converted text to lowercase, removed stopwords and unnecessary symbols, and prepared the text for analysis.
5. **Bag of Words:** Converted text into numerical features using term frequency.
6. **Naive Bayes:** Applied the Naive Bayes classification algorithm to classify sentiment.
7. **Test and Score:** Evaluated model performance using stratified 5-fold cross-validation.

## Model Evaluation Results

The Naive Bayes model was evaluated using the Test and Score widget in Orange Data Mining.

| Metric | Result |
|---|---:|
| AUC | 0.770 |
| Classification Accuracy | 60.4% |
| F1 Score | 0.602 |
| Precision | 0.604 |
| Recall | 0.604 |
| MCC | 0.405 |

The model achieved 60.4% classification accuracy. The AUC score of 0.770 indicates its ability to distinguish between sentiment classes.

## Repository Contents

- `Tweets.csv` – Twitter dataset.
- `tweets.ows` – Orange Data Mining workflow.
- `screenshots/` – Workflow and model evaluation screenshots.

## How to Run the Project

1. Install [Orange Data Mining](https://orangedatamining.com/).
2. Clone or download this repository.
3. Open `tweets.ows` in Orange Data Mining.
4. If prompted, locate the `Tweets.csv` dataset.
5. Run the workflow and open the Test and Score widget to view the evaluation results.

## Future Enhancements

- Use the complete dataset instead of a 5,000-tweet sample.
- Develop an interactive dashboard for sentiment distribution and trend analysis.
- Add word clouds and real-time sentiment visualizations.
- Explore improvements to model accuracy.

## Author

**Anushka Gunwant Kusare**