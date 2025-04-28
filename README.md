# Harshada-Elevate_-labs_-task-3
This project was completed as part of an AI & ML internship using Google Colab and Python. It focuses on applying Linear Regression to predict housing prices based on various features in the Housing.csv dataset.

🔍 Summary of Tasks Performed

✅ 1. Data Import and Exploration
Loaded the dataset using pandas
Used .info(), .describe() to understand data types and missing values

✅ 2. Data Preprocessing
Label Encoded binary categorical columns (mainroad, guestroom, basement, etc.) into 0 and 1.
Applied One-Hot Encoding for the furnishingstatus column.

✅ 3. Train-Test Split
Split the dataset into training and testing sets using 80%-20% ratio.

✅ 4. Model Building
Built a Linear Regression model using sklearn.linear_model.LinearRegression()
Fitted the model on the training data.

✅ 5. Model Evaluation
Calculated:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R-squared (R²) score

✅ 6. Visualization
Created a scatter plot for Area vs Price to visualize predictions vs actual values.

✅ 7. Coefficients Interpretation
Extracted and displayed the coefficients for each feature to interpret the model.

📊 Tools & Libraries Used
Google Colab (Python 3)
pandas, numpy
matplotlib, seaborn
scikit-learn


