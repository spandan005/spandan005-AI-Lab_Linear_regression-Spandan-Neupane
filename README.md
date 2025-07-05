# spandan005-AI-Lab_Linear_regression-Spandan-Neupane

📊 Linear Regression: Predicting English Marks from Maths This project demonstrates how to apply simple linear regression using Python to predict English scores based on Maths scores of students.
🚀 Features Uses Pandas for data manipulation.
Calculates mean-centered values, squared deviations, and product terms.
Computes the regression equation manually (no scikit-learn).
Predicts English marks given a new Maths score.
Visualizes data points and the regression line using Matplotlib.
📁 File Overview main.py: Main Python script containing:
Dataset of 5 students.
Manual computation of regression coefficients.
Data visualization with the regression line and prediction point.
📷 Example Output A table of students' scores with intermediate calculations (x, y, x², y², x·y).
Regression equation:
ini Copy Edit Y = a + bX Graph:
Blue dots: Actual data
Red line: Regression line
Green X: Predicted value for Maths = 45
🧠 Math Behind the Code Regression line: Y = a + bX, where:
b = Σ(x·y) / Σ(x²)
a = Ȳ - b·X̄
📦 Requirements Python 3.x
pandas
matplotlib
Install dependencies:
bash Copy Edit pip install pandas matplotlib ▶️ How to Run bash Copy Edit python main.py 📌 Prediction Example Predicting English marks when Maths = 45
