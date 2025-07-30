# Supply Chain Analysis Project

This project focuses on analyzing supply chain data to identify patterns, assess delivery risks, and visualize geographic performance. The analysis aims to provide insights that can help improve supply chain efficiency and reduce delays.

##  Tools & Technologies

- **Python (Pandas, NumPy)** – data manipulation and feature engineering  
- **Scikit-learn** – modeling pipeline, preprocessing, classification, evaluation  
- **Matplotlib & Seaborn** – data visualization and feature importance plotting  
- **Statistical tests** – Cramér’s V and Chi-squared test for feature significance  
- **Jupyter Notebook** – interactive development environment

## Workflow Overview

1. **Data Preprocessing**
   - Cleaned raw order data
   - Encoded categorical features using OneHotEncoder
   - Engineered key features like `Shipping Route` and `Route Delay Rate`

2. **Exploratory Analysis**
   - Analyzed relationships between delay risk and features such as shipping mode, customer segment, and order month
   - Identified statistically significant variables using Cramér’s V

3. **Modeling**
   - Trained and evaluated two classification models:
     - **Logistic Regression** (baseline)
     - **Random Forest Classifier** (non-linear)
   - Metrics: Accuracy, Precision, Recall, F1, AUC

4. **Results**
   - **Random Forest outperformed Logistic Regression**, with higher AUC and recall
   - Most important features: `Shipping Mode`, `Route Delay Rate`, and `Customer Segment`

5. **Visualization**
   - Bar chart of top 20 feature importances
   - Heatmap and route-level analysis of high-risk shipping paths

## Key Insight:

Shipping mode and route history are strong predictors of late delivery. Integrating route-level risk features significantly improves model performance.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
