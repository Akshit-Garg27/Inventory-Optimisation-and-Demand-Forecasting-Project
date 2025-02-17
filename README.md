# Inventory Optimization and Demand Forecasting Analysis

This project focuses on analyzing and optimizing inventory management through data-driven techniques. By employing advanced statistical models, ABC analysis, and Economic Order Quantity (EOQ) calculations, actionable insights into demand forecasting, inventory turnover, and cost-saving opportunities are provided.

## Key Features

* **Demand Forecasting:**
    * **Seasonality Analysis:** Identified weekly and monthly sales trends. Notable sales peaks on Thursdays and Fridays and significant declines on Sundays. A sharp sales drop was observed in February, highlighting strong seasonality effects.
    * **Forecasting Model:** Utilized Autoregressive Moving Average (ARMA) for time-series forecasting. Achieved R-squared of 0.7 but observed high MAPE (59%) due to abrupt sales drops. Projected March sales quantity to be 254,853 units.
    * **Incorporating Seasonality:** Used the Sarimax Model using Fourier Series and Deterministic proccess integrated the seasonality factor and Updated Model (with Seasonality): MAPE = 54.73%, R² = 0.884 .

* **ABC Analysis:**
    * Categorized brands based on sales volume:
        * Category A: Top-performing brands (12% of total, generating 1.5M sales).
        * Category B: Mid-range brands (sales between 100-1,000 units).
        * Category C: Majority of brands (4677), contributing only 114k sales.
    * Highlighted opportunities for improvement in Category B and C through R&D, marketing, and supply chain strategies.

* **EOQ and Reorder Point Analysis:**
    * **EOQ Insights:** Analyzed variability in optimal order quantities. Identified demand patterns and cost-saving opportunities using a log-scale distribution graph.
    * **Reorder Point Analysis:** Calculated safety stock levels to prevent stockouts and overstocking. Observed majority of brands with reorder points between 0-199 units (primarily Category C).

* **Lead Time Analysis:**
    * Measured average lead times for inventory restocking: Majority experienced lead times exceeding one week.
    * Optimized ordering strategies to account for lead time variability.

* **Inventory Value Optimization:**
    * **Year-End Insights:** Total inventory value: $70M. EOQ-based model projected inventory value of $17M, saving approximately $53M.
    * **Cost Savings:** Potential annual savings of $250k-$500k for top brands. Highlighted need for ongoing model refinements to prevent stockouts and minimize carrying costs.

* **Inventory Turnover Analysis:**
    * Turnover ratio: 4.2
    * Inventory replenished every 86 days.
    * Benefits: Reduced carrying costs, improved cash flow, and enhanced customer satisfaction.
    * Challenges: Risk of stockouts and competitive pressures.

## Technologies Used

* Python: Data analysis and modeling.
* Statsmodels & Sklearn: Time-series and regression modeling.
* Pandas: Data manipulation.
* Matplotlib & Plotly: Visualization.

## Results

* Optimized inventory management strategies.
* Identified cost-saving opportunities totaling $74M.
* Improved demand forecasting accuracy and actionable insights for inventory planning.

## Future Enhancements

* Incorporate additional data for better model accuracy.
* Explore advanced machine learning models for demand forecasting.
* Implement real-time inventory monitoring.

## License

This project is licensed under the MIT License.
