# Fake-News-Prediction-System-

A concise, end-to-end notebook that flags online news articles as real (0) or fake (1).
The pipeline cleans raw headline–body text with NLTK stop-word removal and Porter stemming, converts it to TF-IDF vectors, then trains a Logistic Regression classifier on 20,800 labelled articles.
Everything is pure scikit-learn—no deep-learning GPU required—yet reaches around 93% accuracy on a held-out test split.
Use it as a fast baseline for misinformation research, classroom demos, or a starting point before upgrading to transformer models.
Simply open the notebook, run all cells, and start predicting authenticity for any news snippet in seconds.
