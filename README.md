# Movie Recommendation
This project aims to recommend movies to users based on their movie preferences using a cosine similarity model.

## Data
The dataset used for this project is the MovieLens 100K dataset, which is a dataset of movie ratings by users. It consists of 100,000 ratings with 4 features: user_id, movie_id, rating, and timestamp.

## Methodology
The following steps were taken to build the movie recommendation system using cosine similarity:

## Data preprocessing
Cosine similarity calculation
Movie recommendation
The data preprocessing step involved creating a user-movie matrix with the ratings as the values. The matrix was then normalized to account for the difference in rating scales between users.

The cosine similarity calculation involved calculating the cosine similarity between the user-movie matrix and the movie-movie matrix. The cosine similarity is a measure of similarity between two vectors, and in this case, it measures the similarity between movies based on the ratings given by users.

The movie recommendation step involved selecting a user and calculating the cosine similarity between the user's movie ratings and all the other movies in the dataset. The top N movies with the highest cosine similarity scores were recommended to the user.

## Results
The movie recommendation system using cosine similarity was able to successfully recommend movies to users based on their movie preferences. The system was able to capture the underlying patterns in the data and recommend movies that were similar to the user's preferences.

## Usage
To use the movie recommendation system, follow these steps:

Clone the repository.
Install the required packages using pip install -r requirements.txt.
Run the recommendation.py file.
Enter a user_id to get movie recommendations for that user.
Conclusion
In conclusion, this project built a movie recommendation system using cosine similarity that was able to recommend movies to users based on their movie preferences. The project used various data preprocessing and machine learning techniques to build the recommendation system. The system can be improved by using more advanced machine learning models and incorporating more features such as movie genre and director.
