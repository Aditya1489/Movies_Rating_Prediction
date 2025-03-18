# Movies_Rating_Prediction
## 📌 Project Overview

This project aims to build a predictive model to estimate movie ratings based on various attributes such as genre, director, cast, and other relevant factors. The model leverages machine learning and deep learning techniques to analyze patterns in the data and make accurate predictions.

## 📊 Dataset

The dataset used for this project is [IMDb_Movies_India.csv](https://github.com/Aditya1489/Movies_Rating_Prediction/blob/main/IMDb_Movies_India.csv)
, containing details about movies released in India. It includes attributes like:

* Year 
* Duration 
* Genre 
* Rating 
* Votes
* Director
* Genre_Average_Rating
* Director_Average_Rating
* Actor1_Average_Rating
* Actor2_Average_Rating
* Actor3_Average_Rating

## 🔧 Data Preprocessing

##### To ensure high-quality predictions, the dataset undergoes several preprocessing steps:

* Handling Missing Values: Imputed missing values using appropriate techniques.

* Encoding Categorical Variables: Converted non-numeric features into numerical format using encoding techniques.

#### Feature Engineering:

* Derived features such as director success rate and average rating of similar movies.

* Scaled numerical features for better model performance.

## 🏗 Model Development

##### The predictive model is developed using Keras' Sequential API, incorporating:

* Multiple Dense layers with activation functions.

* Dropout layers to prevent overfitting.

* Adam optimizer for efficient training.

* The dataset is split into training and testing sets using `train_test_split()` to evaluate model performance effectively.

## 📈 Model Evaluation

##### The model is assessed using appropriate evaluation metrics, ensuring it provides reliable rating predictions. Key performance metrics include:

* Mean Squared Error (MSE) = 0.3788870558837424

* Mean Absolute Error (MAE) = 0.43706560514319964

* R² Score = 0.7951553550649397

## 🎯 Expected Outcome

* A well-trained model capable of accurately predicting movie ratings based on given inputs.

* Insights into the factors influencing movie ratings.

* A pre-trained model saved as a pickle file for easy deployment and reuse.

📥 Download the Model: [Movie_rating_prediction_model.pkl](Movie_rating_prediction_model.pkl)

## 📜 Documentation

A detailed explanation of the approach, preprocessing techniques, and model evaluation is provided in the repository [Movies_Rating_Prediction](https://github.com/Aditya1489/Movies_Rating_Prediction) folder.

## ✨ Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## 📌 Author

Aditya Chavhan

[LinkedIn](https://www.linkedin.com/in/aditya-chavhan-5710ba250/)

[GitHub](https://github.com/Aditya1489)
