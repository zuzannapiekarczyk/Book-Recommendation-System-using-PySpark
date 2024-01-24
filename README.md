# Book-Recommendation-System-using-PySpark

## Project Overview

This project focuses on building a book recommendation system using PySpark, specifically implementing the Alternating Least Squares (ALS) collaborative filtering algorithm. The project follows the guidelines provided in the Spark documentation for collaborative filtering ([Spark Collaborative Filtering Documentation](https://spark.apache.org/docs/latest/ml-collaborative-filtering.html)).

### Project Components:

1. **Prepare Dataset for Recommendation System (ALS - item/user/rating):**
   - Collect and preprocess the dataset suitable for collaborative filtering, including item/user/rating information.

2. **Create Collaborative Filtering Model:**
   - Implement the collaborative filtering model using ALS with specified hyperparameters.
   - Calculate the prediction error to evaluate the model's performance.

3. **Model Tuning with Cross-Validation:**
   - Utilize cross-validation techniques, including CrossValidator and ParamGridBuilder in PySpark.
   - Experiment with different hyperparameter combinations to achieve a better-performing model than in step 2.

Feel free to explore the code, adapt it to different datasets, and experiment with various hyperparameter values to enhance the recommendation system. Happy exploring!
