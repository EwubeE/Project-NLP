# Project-NLP
Sentiment Analysis on Movie Reviews
## Project Overview

This project presents a sentiment analysis system designed to automatically categorize movie reviews as either **positive** or **negative**. <br> Using the **Stanford IMDb Large Movie Review Dataset**, which contains 50,000 reviews, the system employs a comprehensive NLP workflow that includes text preprocessing, stop-word removal, lemmatization, TF-IDF vectorization, and classification with a Linear Support Vector Machine (SVM).

The trained model achieved **87.5% accuracy** on the IMDb test set, demonstrating strong predictive performance. To evaluate its ability to generalize, the model was tested on the **Cornell Movie Review Dataset** without additional training, achieving **86.1% accuracy**. The model also proved effective at handling reviews with mixed opinions by correctly determining the prevailing sentiment.
