# Movie-Recommendation-System

Implementation of Movie Recommendation System in Pyton using MovieLens Dataset which contains 100,000 ratings from 943 users with a selection of 1682 movies.

Libraries used:
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Sklearn

Memory-based Collaborative Filtering (User-Item filtering as well as Item-Item filtering) is done by determining the Similarity among Users and Items.

Cosine Similarity is used as the Distance Metric.

Dataset is splitted into Train and Test Dataset and the predictions are made considering the whole Dataset so that the predictions can be compared with the Test Dataset for evaluating the performance of both the Models.

Root Mean Squared Error is calculated for evaluating the performance of the Models.
