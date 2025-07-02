📈 Stock Price Prediction using XGBoost & CatBoost
This project leverages machine learning models—XGBoost Regressor and CatBoost Regressor—to predict stock prices based on historical market data. After extensive tuning and validation, the best-performing model achieves an R² score of ~0.76, indicating a reasonably strong predictive capability.

--Project Overview
Dataset: Historical stock price data (with features like Open, High, Low, Volume, etc.).

Approach: Trained and tuned multiple ML regression models using GridSearchCV and RandomizedSearchCV.

Final Models:

XGBoost Regressor (Best R²: 0.766)

CatBoost Regressor (R²: 0.761)

 Models Used
✅ XGBoost Regressor

Performance:

MAE: 122.70

RMSE: 229.40

R² Score: 0.766

✅ CatBoost Regressor
Performance:

MAE: 126.02

RMSE: 231.80

R² Score: 0.761

📊 Evaluation Metrics
MAE (Mean Absolute Error): Measures average prediction error in units.

RMSE (Root Mean Squared Error): Penalizes large errors more heavily.

R² Score: Measures variance explained by the model.

📁 Project Structure
├── stonks predict.ipynb               # Main Jupyter Notebook
├── README.md                  # Project overview
├── TCS.csv                    # Data files directory

--Key Learnings
-Tried both classifiers and regressors, ultimately used regressors for better real-world accuracy.

-Learned importance of hyperparameter tuning using GridSearchCV and RandomizedSearchCV.

-Discovered that regression is more appropriate than classification for continuous-valued stock prediction.

--Limitations
-Model does not directly predict "tomorrow's" price.

-Market is influenced by many external factors (news, sentiment) that are not included.

-Accuracy (R² ≈ 0.76) is decent but not reliable enough for real-time trading.

📌 How to Run
-Clone the repo and Run jupyter notebook 
