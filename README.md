# PositiveReviewModel
### Overview
The Positive Review Model is a project that aims to distinguish the sentiment of book reviews, determining whether they are positive or negative. The model utilizes data preprocessing techniques, vectorization with TF-IDF (Term Frequency-Inverse Document Frequency), and a neural network built using the Keras library.

### Features
Data Preprocessing: The project employs Pandas DataFrame and NumPy for efficient data handling and preprocessing. This ensures that the input data is well-organized and ready for further analysis.

TF-IDF Vectorization: Natural language sentences are converted into numerical vectors using the TF-IDF technique. This process captures the importance of words in a document relative to a corpus, providing a meaningful representation for the neural network.

Neural Network Model: The core of the project is a neural network model built using the Keras library. The architecture is designed to learn and distinguish the sentiment of book reviews based on the vectorized representations of sentences.

Metrics: The model's performance is evaluated using accuracy as the metric. The accuracy achieved is 83.1%, showcasing the effectiveness of the Positive Review Model in classifying sentiments.

### Requirements
Python 3.x
TensorFlow
Keras
Pandas
NumPy
