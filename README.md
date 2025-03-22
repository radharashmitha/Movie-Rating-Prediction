# Movie-Rating-Prediction
## Project Overview
This project predicts **IMDb movie ratings** based on attributes like **duration, genre, director, and actors**.  
We use **machine learning models** to analyze Indian movies and provide **accurate rating predictions**.

## Features
✔ Data Preprocessing (Handling Missing Values, Encoding Categorical Data)  
✔ Feature Engineering (Director Success Rate, Genre Popularity, etc.)  
✔ Model Training (Linear Regression, Decision Tree, Random Forest)  
✔ Model Evaluation (R² Score, MAE, RMSE)  
✔ Selection of the **Best Performing Model**   

---

## 📂 Dataset Information
The dataset is collected from **IMDb** and contains information about Indian movies.

| Column Name | Description |
|-------------|------------|
| `Name` | Movie Title |
| `Year` | Release Year |
| `Duration` | Movie Length (minutes) |
| `Genre` | Movie Genre(s) |
| `Rating` | IMDb Rating (Target Variable) |
| `Votes` | Number of IMDb Votes |
| `Director` | Movie Director |
| `Actor 1`, `Actor 2`, `Actor 3` | Main Actors in the Movie |

---

## Steps to Run the Project  
### **Open & Run the Google Colab Notebook**
1. Open **[Movie Rating Prediction.ipynb]** in **Google Colab**.
2. Upload the dataset **`IMDb Movies India.csv`** if prompted.
3. Run all cells **sequentially** to:
   - **Preprocess the data** (handle missing values, encode categorical features).
   - **Train machine learning models** (Linear Regression, Decision Tree, Random Forest).
   - **Evaluate model performance** and **predict IMDb movie ratings**.
