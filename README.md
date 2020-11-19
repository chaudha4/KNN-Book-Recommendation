# Book Recommendation using K-Nearest Neighbors

The k-Nearest Neighbors algorithm or KNN for short is a very simple technique.

The entire training dataset is stored. When a prediction is required, the k-most similar records to a new record from the training dataset are then located. From these neighbors, a summarized prediction is made.

## Nearest Neighbors

The principle behind nearest neighbor methods is to find a predefined number of training samples closest in distance to the new point, and predict the label from these.

We use [sklearn.neighbors](https://scikit-learn.org/stable/modules/neighbors.html#unsupervised-neighbors) package to find the books that are nearest neigbors to a given book. Those neighbors are the recommendations !!


