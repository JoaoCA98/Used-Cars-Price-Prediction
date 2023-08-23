# Used Car Price Prediction
[Link to Notebook](https://github.com/JoaoCA98/Used-Cars-Price-Prediction/blob/main/Capstone_Project_Joao_Ascensao.ipynb) [Dataset](https://github.com/JoaoCA98/Used-Cars-Price-Prediction/blob/main/used_cars.csv)
## Project Overview

This project aims to predict used car prices in the Indian market using machine learning techniques. The pre-owned car market has been rapidly growing, and accurately predicting car prices can provide valuable insights for both buyers and sellers. In this project, we analyze the Cars4U dataset to gain insights into the factors influencing car prices and develop a predictive model for price estimation.

## Key Findings and Insights

Our analysis of the Cars4U dataset has revealed several significant findings:

- Mumbai, Hyderabad, and Kochi have the highest number of cars.
- Diesel and petrol are the most common fuel types.
- Manual transmission cars dominate the market.
- Cars are primarily owned by first-owner class individuals.
- There's a positive linear relationship between the log-transformed variables 'Price' and 'Power'.
- Median car prices decrease as they age.
- The price range expands significantly for more recent cars.

## Proposed Model: Hyper-Tuned MLP

Based on our evaluation of various models, we propose the hyper-tuned Multi-Layer Perceptron (MLP) model as the final solution for predicting used car prices. This model demonstrated the highest R-squared values and the lowest RMSE values on both training and testing sets, indicating its ability to accurately capture and generalize data patterns.

## Problem and Solution Summary

### Problem:
Cars4U, a used car sales platform, seeks to accurately predict the prices of used cars in the Indian market. Accurate price predictions can help the platform establish competitive pricing strategies and increase profitability.

### Proposed Solution:
We employ a hyper-tuned MLP model to predict used car prices. This model excels in capturing non-linear relationships and utilizes critical variables such as car power and production year for accurate predictions.

## Implementation Recommendations

- Seamlessly integrate the hyper-tuned MLP model into the Cars4U platform.
- Continuously update the model with new data to maintain accuracy.
- Collaborate with stakeholders to gather feedback and ensure the pricing strategy aligns with their needs.
- Monitor the model's performance to identify areas for improvement.

## Benefits and Costs

**Benefits:**
- Improved customer satisfaction and increased sales.
- Enhanced competitiveness in the market.
- Data-driven decision-making based on accurate pricing predictions.

**Costs:**
- Initial investment in model development, integration, and maintenance.
- Potential costs associated with training, support, and data security.

## Key Risks and Challenges

- **Model Performance:** The model's accuracy may decrease over time due to changing market trends or data quality.
- **Data Security:** Protecting sensitive customer and business data used for model training and prediction.
- **Resistance to Change:** Stakeholders may resist adopting new pricing strategies or technologies.

## Next Steps and Further Analysis

- Investigate other machine learning models, such as ensemble models like XGBoost, to improve performance.
- Experiment with untransformed variables for potential performance gains.
- Consider using grid search for hyperparameter optimization.
- Explore the model's viability in different vehicle market segments and geographic areas.

## Acknowledgments

We would like to acknowledge the Cars4U dataset and the contributions of the data science community in providing resources and guidance.
