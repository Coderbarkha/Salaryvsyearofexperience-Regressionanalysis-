# Salary Prediction Using Linear Regression

## 📌 Project Overview
This project demonstrates the implementation of **Simple Linear Regression** to predict salaries based on years of experience. It is built using **Python** in Google Colab and utilizes **scikit-learn** for training and evaluating the model. The dataset used contains two features:
- **YearsExperience** (Independent Variable)
- **Salary** (Dependent Variable)

## 📂 Dataset
The dataset used is **Salary_dataset.csv**, which contains real-world salary data based on experience.

## 🚀 Features Implemented
- **Data Preprocessing:**
  - Load dataset from Google Drive.
  - Handle missing values by filling them with the mean of the respective column.
  - Split the dataset into **80% training** and **20% testing**.

- **Model Training:**
  - Implement **Simple Linear Regression** using `LinearRegression` from `sklearn`.
  - Train the model using **YearsExperience** as input and **Salary** as the output.
  - Display model parameters (Slope & Intercept).

- **Data Visualization:**
  - Scatter plots for **training and testing data**.
  - Plot **regression line** to show predictions.

- **Model Evaluation:**
  - Compute **Predicted Salary** values.
  - Calculate **Deviation** (Difference between actual and predicted salaries).
  - Compute **R-squared (R²) Score** to measure model accuracy.

## 📜 Code Explanation
1. **Load Data** from Google Drive.
2. **Handle Missing Values** by filling them with the mean.
3. **Split Data** into training and testing sets.
4. **Train the Model** using `LinearRegression`.
5. **Predict Salaries** for both training and testing sets.
6. **Visualize Results** using scatter plots and regression lines.
7. **Evaluate Model Performance** using R² score.

## 📊 Results
- The trained regression model predicts salaries based on experience.
- The **R-squared score** helps measure the model’s accuracy.
- Regression line plots visualize how well the model fits the data.

## 🛠️ Technologies Used
- **Python** (Google Colab)
- **pandas** (Data Handling)
- **NumPy** (Numerical Computations)
- **Matplotlib** (Data Visualization)
- **scikit-learn** (Machine Learning Model)

## 📌 How to Run the Code
1. Upload **Salary_dataset.csv** to your Google Drive.
2. Open **Google Colab** and run the code.
3. Mount your Google Drive to access the dataset.
4. Train and test the model using `LinearRegression`.
5. View the scatter plots and R² score.

## 🔥 Future Improvements
- Try using **multiple linear regression** by adding more independent variables.
- Test with a larger dataset for better predictions.
- Use **Polynomial Regression** for non-linear relationships.

## 📜 Author
This project was created by **@Coderbarkha** as part of learning **Machine Learning with Python**. 🚀

---
Feel free to contribute or suggest improvements!

