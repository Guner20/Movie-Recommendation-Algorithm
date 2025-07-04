Description:
A neural network-based movie recommendation system using TensorFlow and the MovieLens 100K dataset. The model learns user and movie embeddings and utilizes movie metadata (genres) to generate personalized recommendations.

Features:
* Predicts movie ratings for a given user
* Provides top-N movie recommendations for each user
* Plots training and validation losses (MSE & MAE)

Overview:
By using user and movie embeddings, This model passes concatenated embeddings through dense layers with ReLU activations and Dropout and outputs a predicted rating
user and movie embeddings

For example for user 7, algorithm suggests these movies:
*Eat Drink Man Woman (1994)
*Three Colors: Red (1994)
*Ridicule (1996)
*Leaving Las Vegas (1995)
*Mother (1996)
*Barcelona (1994)
*Saint, The (1997)
*Kids (1995)
*Georgia (1995)
*Double vie de Véronique, La (Double Life of Ve...

