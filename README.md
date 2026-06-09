# Simple Linear Regression: Salary Prediction
This project implements a **Simple Linear Regression** model to predict salary based on years of experience. It covers the complete machine learning workflow, from data preprocessing to model evaluation.
## 🛠 Tech Stack
 * **Scikit-Learn:** Used for model training, data splitting, and linear regression implementation.
 * **Matplotlib & Seaborn:** Used for data visualization.
 * **Pandas & NumPy:** Used for data manipulation and feature selection.
## ⚙️ Workflow & Methodology
This project follows a systematic approach to ensure model reliability:
 1. **Feature Selection:** Identified and isolated the relevant independent variable (Years of Experience) that significantly impacts the target variable (Salary).
 2. **Data Splitting:** Divided the dataset into **Training** and **Testing** sets (using train_test_split) to ensure the model's performance can be evaluated on unseen data.
 3. **Model Training:** Fitted the Linear Regression model specifically on the training data.
 4. **Visualization:**
   * **Scatter Plot:** Visualized the raw distribution of data points.
   * **Regression Plot:** Used seaborn.regplot to plot the regression line against the data, visualizing the "Best Fit Line."
## 🚀 How to Run
 1. Ensure you have Python installed.
 2. Install the required dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   
   ```
 3. Run the script:
   ```bash
   python main.py
   
   ```
## 📈 Summary
By splitting the data, the model avoids overfitting and provides a more accurate reflection of how well the regression line predicts salaries for new, previously unseen data points.
