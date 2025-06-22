# PowerPulse-Household-Energy-Usage-Forecast



## 📊 Project Objectives
- Build regression models to predict **Global Active Power**
- Analyze key factors that influence household energy consumption
- Visualize energy usage trends and predictive performance
- Deliver a reliable and reusable model

---

## 🧠 Skills Used
- Data Cleaning & Preprocessing
- Feature Engineering
- Regression Modeling (Linear, Random Forest, Gradient Boosting, MLP)
- Hyperparameter Tuning (`GridSearchCV`, `RandomizedSearchCV`)
- Evaluation Metrics: RMSE, MAE, R²
- Data Visualization (Matplotlib, Seaborn)
- Model Saving (`joblib`)

---

## 🧾 Dataset
**Name:** Individual Household Electric Power Consumption  
**Source:** UCI Machine Learning Repository  
**Data Includes:**  
- Date, Time, Global Active Power, Reactive Power, Voltage  
- Sub-metering values for different areas of the house

---

## 🧪 Models Used
| Model                 | Description                     |
|----------------------|---------------------------------|
| Linear Regression     | Simple baseline model           |
| Random Forest Regressor | Ensemble method for accuracy     |
| Gradient Boosting Regressor | Boosted trees for higher precision |
| MLP Regressor         | Neural Network-based predictor  |

---

## 🧪 Evaluation Metrics
| Metric | Description |
|--------|-------------|
| ✅ RMSE | Root Mean Squared Error (Lower = Better) |
| ✅ MAE  | Mean Absolute Error (Lower = Better) |
| ✅ R²   | Explains variance (Closer to 1 = Better) |

**Best Model:** Tuned Random Forest Regressor  
Achieved **lowest RMSE & MAE**, and **R² > 0.90**

---

## 📈 Visualizations
- Daily energy usage trends
- Feature importance chart
- Actual vs Predicted comparison
- Error distribution plot
- Weekly usage pattern (Day of week)

---

## 📁 Project Structure

📦 powerpulse/
┣ 📜 powerpulse_notebook.ipynb # Main code notebook
┣ 📊 powerpulse_best_model.pkl # Trained & saved model
┣ 📈 visualizations/ # Trend plots, bar charts
┣ 📄 README.md # This file
┗ 📂 data/
┗ 📄 household_power_consumption.txt

## Conclusion
This project successfully demonstrated the application of machine learning in forecasting household energy usage. By leveraging real-world data and applying advanced regression techniques, we were able to build a highly accurate model that explains user behavior, detects trends, and supports energy optimization goals. The insights gained through feature analysis and visualizations provide a strong foundation for smarter energy management — both for users and providers. This model also serves as a baseline for future enhancements like smart meter integration and dynamic demand-response systems.
