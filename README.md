This project focuses on classifying movie reviews as positive or negative using an LSTM-based deep learning model.
LSTM (Long Short-Term Memory) networks are a special type of Recurrent Neural Network (RNN) that capture long-term dependencies in text, making them ideal for sentiment analysis and other NLP tasks.

The model is built using Keras, a high-level deep learning library running on top of TensorFlow.
I used the IMDB Movie Review dataset (50,000 labeled reviews) from Kaggle:

Dataset: https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

The dataset contains:

50,000 reviews

25,000 positive, 25,000 negative

Balanced, labeled text classification dataset

Two columns:

review (text)

sentiment (positive/negative)
Model Architecture

The model follows a simple and effective deep learning pipeline:

Embedding Layer – Converts words into dense vector representations

LSTM Layer – Captures sequence information

Dense Layer with Sigmoid – Binary sentiment classification

Optimizer – Adam

Loss Function – Binary Crossentropy

This architecture allows the model to learn sentiment patterns from raw text and generalize well on unseen reviews.
Project Repository Links

🔗 My GitHub Profile: https://github.com/ChallaSiri

🔗 Project Repository: https://github.com/ChallaSiri/LSTM-sentiment-analysis
References & Helpful Resources

TensorFlow/Keras Documentation
🔗 https://www.tensorflow.org/api_docs/python/tf/keras

LSTM Sentiment Analysis Example
🔗 https://github.com/sanjay-raghu/sentiment-analysis-using-LSTM-keras/blob/master/lstm-sentiment-analysis-data-imbalance-keras.ipynb

Step-by-step LSTM Sentiment Guide
🔗 https://towardsdatascience.com/sentiment-analysis-using-lstm-step-by-step-50d074f09948

Kaggle LSTM Tutorial
🔗 https://www.kaggle.com/ngyptr/lstm-sentiment-analysis-keras

YouTube Tutorial (LSTM Sentiment Analysis)
🔗 https://www.youtube.com/watch?v=qpb_39IjZA0

LSTM/GRU Illustrated Explanation
🔗 https://towardsdatascience.com/illustrated-guide-to-lstms-and-grus-a-step-by-step-explanation-44e9eb85bf21

Understanding Dense Layers in Keras
🔗 https://medium.com/@hunterheidenreich/understanding-keras-dense-layers-2abadff9b990
