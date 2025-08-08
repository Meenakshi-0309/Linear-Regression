Task 3: Linear Regression - House Price Prediction
Objective
Implement and understand **Simple** & **Multiple Linear Regression** using the `Housing.csv` dataset.  
We predict house prices based on different features such as area, number of bedrooms, etc.

Dataset:
The dataset used is **Housing.csv**.  
It contains features like:
price (Target Variable)
area
bedrooms
bathrooms
stories
mainroad
guestroom
basement
hotwaterheating
airconditioning
parking
prefarea
furnishingstatus

Tools & Libraries:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Steps Followed"
1. **Import & Preprocess Data**
   - Handled categorical variables (`yes`/`no` → 1/0, One-Hot Encoding).
   - Checked for missing values.
   
2. **Train-Test Split**
   - Used 80% training and 20% testing data.

3. **Model Building**
   - Used `LinearRegression` from `sklearn.linear_model`.

4. **Evaluation Metrics**
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score

5. **Visualization**
   - Scatter plot for **Actual vs Predicted**.
   - Regression line for **Area vs Price**.

---

## 📊 Results
Example output (your results may vary slightly):

| Metric   | Value |
|----------|-------|
| MAE      | 116,798.53 |
| MSE      | 2.87e10 |
| RMSE     | 169,352.71 |
| R² Score | 0.6784 |

---

## 📈 Plots
- **Actual vs Predicted Price**  
- **Regression Line** (Area vs Price)

---

## ▶ How to Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `Housing.csv`:
   ```python
   from google.colab import files
   uploaded = files.upload()
