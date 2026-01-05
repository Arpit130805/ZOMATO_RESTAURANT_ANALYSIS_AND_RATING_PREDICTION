# 🍽️ Zomato Restaurant Analysis & Rating Prediction

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** and **Machine Learning–based rating prediction** on the Zomato restaurant dataset.  
The objective is to analyze restaurant trends and build predictive models that estimate restaurant ratings based on cost, location, cuisine, and customer engagement.

---

## 🎯 Objectives
- Analyze restaurant data to identify trends and patterns  
- Understand key factors influencing restaurant ratings  
- Perform data cleaning and preprocessing  
- Build machine learning models for rating prediction  
- Extract business-oriented insights  

---

## 📂 Dataset Description
The dataset contains detailed information about restaurants listed on Zomato, including:

- Restaurant Name  
- Location and City  
- Cuisine Types  
- Average Cost for Two  
- Online Ordering Availability  
- Table Booking Availability  
- Number of Reviews  
- Number of Followers  
- Restaurant Ratings  

The dataset contains missing values and unstructured fields that require preprocessing.

---

## 🧹 Data Preprocessing & Cleaning
The following steps were performed:

- Removal of null and duplicate values  
- Extraction of numerical values from text-based columns  
- Encoding categorical variables  
- Feature scaling for model compatibility  
- Dropping irrelevant or redundant columns  

These steps ensured high-quality input data for analysis and modeling.

---

## 📊 Exploratory Data Analysis (EDA)
EDA was conducted to understand:

- Distribution of restaurant ratings  
- Popular cuisines and restaurant locations  
- Relationship between cost and ratings  
- Impact of online ordering and table booking  
- Correlation between customer engagement and ratings  

Visualizations such as histograms, bar plots, and heatmaps were used.

---

## 🤖 Machine Learning Models
The following regression models were implemented:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

### 📏 Evaluation Metrics
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R² Score  

Ensemble-based models showed better performance due to non-linear feature handling.

---

## 📈 Results & Insights
- Higher customer engagement leads to higher ratings  
- Online ordering has a positive impact on ratings  
- Location and cuisine significantly influence restaurant performance  
- Random Forest Regressor achieved the best prediction accuracy  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📁 Project Structure
- ├── Zomato_Restaurant_Analysis_and_Rating_Prediction.ipynb
- ├── README.md

---

## 🔮 Future Enhancements

- Hyperparameter tuning for improved accuracy
- Model deployment using Flask or Streamlit
- NLP-based sentiment analysis on user reviews
- Recommendation system based on user preferences

---

## 👤 Author

- Arpit
- B.Tech CSE | Aspiring Data Analyst

---

## 🙏 Acknowledgements

- Zomato public dataset
- Open-source Python community
