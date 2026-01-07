 Movie Rating Prediction (Sentiment Analysis)

A Machine Learning project that predicts the IMDb Rating of a movie based on its Plot Description. This project demonstrates the use of Natural Language Processing (NLP) and Linear Regression to analyze text sentiment and assign a numerical score.

 Project Overview
The goal of this project is to understand how textual data (movie plots) correlates with numerical ratings. It allows users to:
1. Analyze the distribution of movie ratings in the top 260 movies.
2. Train a Linear Regression model using TF-IDF vectorization.
3. Predict a rating (0-10) for any new movie plot entered by the user.
4. Interact via a menu system to add new training data dynamically.

 Tech Stack
  Language: Python 3.x
  Environment: Jupyter Notebook
  Libraries:  
    * `pandas` (Data Manipulation)
    * `numpy` (Numerical Operations)
    * `matplotlib` (Data Visualization)
    * `scikit-learn` (Machine Learning & NLP)

 Dataset
The project uses the `tmdb_top260_with_imdb.csv` dataset, which includes:
Title:Name of the movie.
Plot: A short text description of the story.
IMDb Rating: A score from 1.0 to 10.0.
Other metadata: Genre, Director, Actors, etc.
How to Run Locally

 1. Prerequisites
Ensure you have Python installed. You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib scikit-learn


git clone [https://github.com/YourUsername/Movie-Sentiment-Analysis.git](https://github.com/YourUsername/Movie-Sentiment-Analysis.git)
cd Movie-Sentiment-Analysis


==============================
   MOVIE ANALYSIS SYSTEM
==============================
1. Predict Rating for a Plot
2. Add New Movie Data
3. View Dataset Stats
4. Exit
