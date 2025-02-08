# 🎵 Music Mood Prediction and Recommendation System  

## 📌 Project Overview  
This project focuses on developing a **machine learning-based music recommendation system** that classifies songs based on mood and retrieves recommendations accordingly. The system takes **song attributes** as input and predicts the user's **mood** (happy, sad, energetic, or calm). It then suggests songs from a dataset that align with the predicted mood, ensuring a **personalized listening experience**.  

## 🔍 Technical Details  

### 📊 Dataset  
- **Size:** 687 rows (songs)  
- **Features (Xi’s):**  
  - Length, danceability, acousticness, energy, instrumentalness  
  - Liveness, valence, loudness, speechiness, tempo  
  - Key, time signature  
- **Number of Features:** 13  
- **Target Variable (Y):** Mood classification into **happy, sad, energetic, or calm**  

### 🏆 Machine Learning Models Tested  
- **K-Nearest Neighbors (KNN)**  
- **Support Vector Machines (SVM)**  
- **Logistic Regression**  
- **Naive Bayes**  
- **Decision Tree**  

### 🤖 Model Selection  
- The model with the **highest accuracy** or **lowest error (r-score) on the test set** is chosen for deployment.  

## 🎯 Key Features  
✅ Predicts the **mood** of a user based on song attributes.  
✅ Retrieves **recommended songs** from the dataset matching the predicted mood.  
✅ Compares multiple **classification algorithms** to optimize performance.  
✅ Provides a **personalized and data-driven** music-listening experience.  

## 🛠 Tech Stack  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib  
- **Machine Learning Techniques:** Classification, Feature Engineering  

## 🚀 Future Enhancements  
🔹 Expand the dataset for better generalization.  
🔹 Integrate a real-time music streaming API for dynamic recommendations.  
🔹 Implement deep learning techniques for improved mood classification.  

## 📜 License  
This project is developed for **academic and research purposes**. Feel free to use and modify it for learning!  

