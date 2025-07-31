OverView: (Refer to the full report for more details : [Report](<NLP -project report.pdf>))

To classify human emotions in text data using various machine learning models. The goal was to improve understanding of emotional expression in contexts like customer reviews, with potential applications in healthcare, marketing, education, and behavioral prediction.

Dataset:
20,000 labeled sentences
Emotion labels: Anger, Fear, Joy, Love, Sadness, Surprise
Imbalanced distribution (Love and Surprise had fewer samples)

Models Used:
Bidirectional LSTM, Logistic Regression, Random Forest, Feed Forward Neural Network and Naïve Bayes.

Results:
Best performing model was Bidirectional LSTM with an F1 score of 0.89 across all the emotions. Strongest emotion classifications: Joy and Sadness. Weakest performance on: Surprise (least training data)
