# Link Prediction Using SVNS

This research initiative presents an innovative approach that merges SVNS with cosine similarity for link prediction, potentially applicable to a movie recommendation system.

## Datasets
The project utilizes the following datasets:

### MovieLens Dataset

- **Source**: [Link to MovieLens Dataset](https://grouplens.org/datasets/movielens/)

### Twitter Movie Dataset

- **Source**: [Link to Twitter Movie Dataset](https://www.kaggle.com/datasets/tunguz/movietweetings)

### Anime Dataset

- **Source**: [Link to Anime Dataset](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database?select=rating.csv)

## Code

Included in the project are several code files organized into sets:

### Code Set 1 - Link prediction on MovieLens Dataset
This set contains two .ipynb files: one implementing the SVNS model and the other serving as a comparative baseline without SVNS on the MovieLens Dataset.

- `MovieLens_dataset_SVNS.ipynb`: Implements link prediction using SVNS and cosine similarity, on the subset of the top 100 genres and users from the MovieLens Dataset.
- `MovieLens_dataset_without_SVNS.ipynb`: Implements link prediction on the same subset, utilizing average ratings providing a baseline for comparison.

### Code Set 2 - Link prediction on Twitter Movies Dataset
This set also comprises two .ipynb files, each specific to the Twitter Movie Dataset.

- `twitter_movie_dataset_SVNS.ipynb`: Applies SVNS and cosine similarity for link prediction among the top 100 genres and users on the Twitter Movie Datset.
- `twitter_dataset_without_SVNS.ipynb`: Executes link prediction with average ratings on the same data subset, providing a baseline for comparison.

### Code Set 3 - Link prediction on Anime Dataset
Similarly, this set includes two .ipynb files of the implementation for the Anime Dataset.

- `link_prediction_anime_SVNS.ipynb`: Implementation of link prediction with SVNS and cosine similarity, on a subset of the Anime dataset which includes the top 100 genres and users.
- `link_prediction_anime_without_SVNS.ipynb`: Implementation of a link prediction model using average ratings on the same data subset as above.

Each code file also includes the hyperparameter tuning and visualization using residual and prediction error graphs on the top 5 performing models.
Each code set is designed to explore and validate the effectiveness of the SVNS-based model against more conventional methods in different dataset contexts.

## Contact
Abhijay Sai Paladugu
abhijaysaipal@gmail.com