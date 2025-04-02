# Movie Recommendation System.

### Project Overview.
This project implements a Movie Recommendation System using collaborative filtering and content-based filtering. It includes an SVD-based collaborative filtering model and a hybrid model that blends SVD predictions with genre-based similarity scores.

### Data Sources.
The two datasets used are sourced from [Movielens.](https://grouplens.org/datasets/movielens/latest/) They are:
- **ratings.csv:** User ratings for movies.
- **movies.csv:** Movie metadata, including genres.

### Tools.
- Jupyter notebook.
- Tableau.
- Microsoft PowerPoint.

### Data Cleaning/Preparation.
In the data preparation phase, the following tasks were performed:
1. Data loading and inspection.
2. Dropping irrelevant columns.
3. Data cleaning and formatting.

### Exploratory Data Analysis (EDA):
EDA involved:
- Visualizing rating distributions and genre counts.
- Finding the highest and lowest-rated movies.
- Calculating a better rating average.
![image](https://github.com/user-attachments/assets/288c2c97-e8c8-40d6-aeb1-fd8d4f70301e)
![image](https://github.com/user-attachments/assets/7c6a460f-e94e-407a-924c-3a0d9aac6a9d)

### Collaborative Filtering with SVD:
- Trained using surprise library.
- Hyperparameter tuned the model.
- generated predictions for the model.

### Content-Based Filtering:
- Uses cosine similarity on one-hot encoded genres.

### Hybrid Model:
- Blending SVD and content-based filtering scores.

### Evaluation:
- Computing the RMSE and MAE for both models.
![image](https://github.com/user-attachments/assets/60c41af6-8361-4417-8551-27f9fa4708cb)


### Results/Findings:
- The hybrid model was more consistent. 
- The goal was to have errors close to zero on average which is why the SVD model was preferable.

![image](https://github.com/user-attachments/assets/07df6cec-fe5e-478f-beb7-2827dfe9bb84)

### Future Improvements:
- Incorporate additional metadata (e.g., director, cast) into content-based filtering.
- Explore deep learning approaches for recommendations.



  


