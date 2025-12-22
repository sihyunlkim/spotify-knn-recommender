# Spotify Music Recommender (KNN-based)

A machine learning-powered music recommendation system that analyzes audio features to suggest similar tracks from the Spotify dataset using the **K-Nearest Neighbors (KNN)** algorithm.

## 🚀 Project Overview
This project focuses on building an engine that determines music similarity by evaluating various acoustic characteristics such as danceability, energy, and acousticness. It demonstrates a complete data science pipeline, from data preprocessing and exploratory data analysis (EDA) to feature engineering and model deployment.

## ✨ Key Features
* **Feature-Based Analysis**: Processes 10+ audio attributes (e.g., valence, tempo, liveness) to map song similarities.
* **KNN Recommendation Engine**: Utilizes Scikit-learn's KNN model to calculate mathematical distances between tracks for precise matching.
* **Data Visualization**: Includes visual insights into the dataset's trends and feature correlations through EDA.
* **Personalized Recommendations**: Provides users with a curated list of songs based on a selected track's unique audio profile.

## 🛠 Tech Stack
* **Language**: Python 3.x
* **Core Libraries**: 
  * `pandas`, `numpy`: Data manipulation and numerical processing.
  * `scikit-learn`: Implementation of the KNN algorithm.
  * `matplotlib`, `seaborn`: Advanced data visualization.
* **Dataset**: A comprehensive Spotify dataset (`data.csv`) featuring thousands of tracks.

## 📂 Project Structure
* `PTDS.ipynb`: Main Jupyter Notebook containing the data analysis and recommendation logic.
* `data.csv`: The primary dataset utilized for training and generating recommendations.
* `requirements.txt`: List of Python dependencies required to set up the environment.

## ⚙️ Installation & Usage
1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/spotify-knn-recommender.git](https://github.com/your-username/spotify-knn-recommender.git)
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
3. **Run the system**: Open PTDS.ipynb in a Jupyter environment and execute the cells to generate song recommendations.
