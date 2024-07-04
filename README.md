# Book Recommendation System using Machine Learning

## Overview
This project aims to develop a book recommendation system using collaborative filtering techniques. The system leverages user ratings to suggest books that a user might like.

## Dataset
The dataset used for this project is sourced from Kaggle: [Book Recommendation Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset).

## Working
### Data Loading and Preprocessing
1. **Loading Datasets**:
   - **Books Dataset**: Contains book details (ISBN, title, author, year of publication, publisher).
   - **Users Dataset**: Contains user details (user ID, location, age).
   - **Ratings Dataset**: Contains user ratings for books (user ID, ISBN, rating).

2. **Data Cleaning and Preparation**:
   - Renamed columns for better readability.
   - Filtered users with more than 200 ratings to focus on active users.

3. **Matrix Creation**:
   - Created a user-item matrix where rows represent users and columns represent books.

### Model Training
1. **Collaborative Filtering**:
   - Used K-Nearest Neighbors (KNN) for collaborative filtering.
   - Trained the model to find similarities between books based on user ratings.

2. **Model Evaluation**:
   - Evaluated the model using metrics like RMSE (Root Mean Squared Error) to ensure accuracy.

### Book Recommendation
1. **Generating Recommendations**:
   - Provided functions to recommend books based on a given book title.
   - Demonstrated examples of book recommendations using the trained model.

### Model Saving
1. **Saving the Model**:
   - Saved the trained model to a file (`book_recommendation_model.pkl`) for future use.

## Insights
- Collaborative filtering is effective for creating personalized book recommendations.
- Filtering out less active users improves the model's performance.

## Outcomes
- Successfully developed a book recommendation system.
- The system can suggest books based on user preferences with reasonable accuracy.

## Files in the Repository
- `Book Recommendation System.ipynb`: Jupyter notebook containing the complete code for the project.
- `proposal.md`: Proposal document outlining the project objectives and approach.
- `report.md`: Detailed report of the project, including methodology, results, and conclusions.

## Conclusion
This project demonstrates the application of collaborative filtering for book recommendations. By leveraging user ratings, the system can provide personalized book suggestions, enhancing the reading experience.

