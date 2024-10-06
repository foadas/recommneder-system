# Recommender System using Two-Tower Neural Network

This project focuses on building a recommender system using a two-tower neural network architecture, specifically designed for the Digikala website. The main goal was to enhance user experience by providing personalized product recommendations based on user preferences and product features.

## Main Features

- **Two-Tower Neural Network**: Utilizes separate towers for user and product embeddings to capture distinct features effectively.
- **Candidate Generation**: The first step involves generating a list of potential recommendations tailored to user preferences.
- **Ranking**: The second step ranks the generated candidates based on their relevance to the user.
- **Metrics**: Employed factorized top-k and in-batch softmax loss as metrics to evaluate the model's performance.

## Libraries Used

- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
