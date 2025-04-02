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

### Results/Findings:
- The hybrid model was more consistent. 
- The goal was to have errors close to zero on average which is why the SVD model was preferable.

### Future Improvements:
- Incorporate additional metadata (e.g., director, cast) into content-based filtering.
- Explore deep learning approaches for recommendations.


  


