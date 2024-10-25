# **Line of best fit**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![NumPy](https://img.shields.io/badge/NumPy-1.21.0-blue) ![Pandas](https://img.shields.io/badge/Pandas-1.3.0-blue) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.2-yellowgreen)

 **linear regression model** to predict office prices based on office size using gradient descent.
---

## 🚀 **Script**

Given a dataset containing office sizes and prices, we normalize the data and use **gradient descent** to minimize the error. After training for a specific number of epochs, we visualize the final line of best fit.

### Key Features
- **Custom Gradient Descent Implementation**
- **MSE Tracking for Each Epoch**
- **Visualizations for Line of Best Fit and MSE**

---

## 📁 **Dataset**

| Column | Description            |
| ------ | ---------------------- |
| SIZE   | Office size in sq. ft. |
| PRICE  | Price in local currency|

---

## 📊 **I guess how**

1. **Data Preprocessing**: Normalize the 'SIZE' feature for stability during gradient descent.
2. **Model Training**: Use gradient descent to iteratively adjust weights.
3. **Error Computation**: Calculate Mean Squared Error (MSE) at each epoch.
4. **Visualization**: Plot the data points, line of best fit, and MSE over time.

---

## 🧩 **Code Structure**

```plaintext
📦Nairobi_Office_Price_Prediction
 ┣ 📂data
 ┃ ┗ 📜Nairobi_Office_Price.csv
 ┣ 📂notebooks
 ┃ ┗ 📜Linear_Regression_with_GD.ipynb
 ┣ 📜README.md
 ┣ 📜model.py
 ┗ 📜plot.py

# **I'm also as surprised and dumbfounded as you are... done this for school so yeah **
