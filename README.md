# Yahoo-Finance-Analysis

## **1. Project Overview**

The goal of this project is to predict stock prices using historical data and machine learning techniques. The predictions are visualized using Tableau to provide deeper insights.

### **Features of the Project**
1. Data preprocessing and handling missing values.
2. Exploratory Data Analysis (EDA), including visualizations like heatmaps.
3. Implementation of the Random Forest regression model.
4. Error analysis (MAE, MSE, RMSE).
5. Interactive visualizations using Tableau.

---

## **2. How to Use This Repository**

### **Step 1: Clone the Repository**
```bash
git clone https://github.com/yourusername/stock-price-prediction.git
cd stock-price-prediction
```

### **Step 2: Install Dependencies**
Install the required Python libraries:
```bash
pip install -r requirements.txt
```

### **Step 3: Run the Notebooks**
Execute the Jupyter Notebooks step-by-step:
1. **01_preprocessing.ipynb**: Data cleaning and preprocessing.
2. **02_exploratory_analysis.ipynb**: Analyze data trends and patterns.
3. **03_modeling.ipynb**: Train and evaluate the Random Forest model.
4. **04_visualization_tableau.md**: Visualize results in Tableau.

---

## **3. Tableau Integration**

Visualizations in Tableau include:
- Heatmap of monthly trading volumes.
- Comparison of actual vs predicted stock prices.
- Error trend analysis.

### Steps for Tableau Visualization:
1. Import `prediksi_harga_saham.csv` or `prediksi_harga_saham_dengan_error.csv` into Tableau.
2. Follow the instructions in **04_visualization_tableau.md** for creating dashboards.

---

## **4. Key Findings**

### **Exploratory Analysis**
- Significant seasonal patterns were observed in trading volumes.
- Trends indicate volatility spikes during specific months.

### **Model Performance**
- Mean Absolute Error (MAE): `...`
- Root Mean Squared Error (RMSE): `...`

### **Predictions**
- Predicted stock prices align closely with actual prices, showing the model's reliability.
- Error trends reveal potential overfitting in certain time periods.

---

## **5. Contributing**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Create a Pull Request.

---

## **6. License**
This project is licensed under the MIT License. See the LICENSE file for details.
