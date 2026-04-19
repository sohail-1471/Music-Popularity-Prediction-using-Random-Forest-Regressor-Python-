# Music Popularity Prediction using Random Forest Regressor (Python)

## 📌 Project Overview

This project builds a machine learning model using the **Random Forest Regressor** to predict music popularity based on audio features and metadata from Spotify.
The objective is to analyze how different musical and contextual attributes influence a track’s popularity and to develop a predictive model that estimates popularity scores.

---

## 📊 Dataset Description

The dataset is sourced from Spotify and includes the following features:

* **Track Name** – Name of the song
* **Artists** – Artist(s) of the track
* **Album Name** – Name of the album
* **Album ID** – Unique album identifier
* **Track ID** – Unique track identifier
* **Popularity** – Target variable (popularity score)
* **Release Date** – Date of release
* **Duration (ms)** – Length of the track
* **Explicit** – Explicit content indicator
* **External** – External presence indicator

### 🎵 Audio Features:

* **Danceability** – How suitable a track is for dancing
* **Energy** – Intensity and activity level
* **Key** – Musical key of the track
* **Loudness** – Overall loudness in decibels
* **Mode** – Major or minor scale
* **Speechiness** – Presence of spoken words
* **Acousticness** – Likelihood of acoustic sound
* **Instrumentalness** – Presence of vocals
* **Liveness** – Probability of live performance
* **Valence** – Musical positivity
* **Tempo** – Beats per minute (BPM)

---

## 🎯 Objectives

* Build a Random Forest model to predict music popularity
* Identify key factors influencing song popularity
* Analyze relationships between audio features and popularity
* Evaluate model performance using regression metrics

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Pycharm

---

## 🔍 Project Workflow

### 1. Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Feature selection and cleaning

### 2. Exploratory Data Analysis (EDA)

* Feature distribution analysis
* Correlation heatmap
* Popularity trends across features

### 3. Feature Engineering

* Transforming release date
* Normalizing numerical features

### 4. Model Building

* Implementing **Random Forest Regressor**
* Splitting dataset into training and testing sets

### 5. Model Evaluation

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 6. Visualization

* Feature importance plot
* Actual vs predicted popularity

---

## 📈 Key Insights

* Audio features like energy, danceability, and valence strongly impact popularity
* Loudness and tempo contribute to listener engagement
* Certain genres or artist-related factors influence popularity trends

---

## 📌 Future Improvements

* Hyperparameter tuning for better accuracy
* Compare with other models (XGBoost, Linear Regression)
* Deploy model using Streamlit or Flask
* Add recommendation system features

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📬 Contact

For any questions or suggestions, feel free to reach out. Email ID: sohailzareen279@gmail.com
