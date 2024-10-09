# House Price Prediction using Linear Regression

## Project Overview

This project demonstrates how linear regression can be used to predict house prices based on various features. It leverages a dataset of housing prices and applies machine learning techniques such as gradient descent and the normal equation to find optimal predictions.

The key goal is to build a model that can accurately predict house prices, providing insight into the factors that drive home values.

## Key Features
- **Data Preprocessing:** The dataset is cleaned by removing missing and duplicate values, and the target feature (`Price`) is constrained within reasonable limits to prevent outliers from skewing the model.
- **Feature Standardization:** The input features are standardized to ensure efficient gradient descent convergence.
- **Gradient Descent Optimization:** Implemented from scratch to minimize the cost function and iteratively improve the accuracy of predictions.
- **Normal Equation:** Alternative method to compute the optimal theta parameters directly, providing a comparison to the gradient descent approach.
- **Model Evaluation:** The performance of the model is assessed using Mean Squared Error (MSE) to compare actual vs. predicted house prices.
  
## Technology Stack
- **Programming Language:** Python
- **Libraries:** `numpy`, `pandas`, `matplotlib`
- **Techniques:** Linear Regression, Gradient Descent, Normal Equation

## Workflow

1. **Data Loading & Cleaning**
   - Loaded the house price dataset and removed missing and duplicate entries.
   - Filtered prices to avoid extreme outliers that may distort predictions.

2. **Data Standardization**
   - Standardized the features to bring them to the same scale, improving the learning process of gradient descent.

3. **Gradient Descent Implementation**
   - Developed a custom gradient descent function to minimize the cost function. The learning rate and cost difference thresholds are carefully tuned to prevent divergence.
   - Visualized the cost function's descent over iterations.

4. **Model Evaluation**
   - Used both the custom gradient descent implementation and the normal equation method to calculate the optimal parameters.
   - Compared model predictions using MSE and plotted results for better interpretation.

## Visualizations

- **Cost vs. Iterations Plot:** Shows how the cost decreases over time as the model learns.
- **Prediction vs. Actual Plot:** Visual comparison of the actual house prices vs. the predicted prices, giving insight into model performance.

## Results

- **Gradient Descent:** Achieved a Mean Squared Error (MSE) of *X* for the test set.
- **Normal Equation:** Achieved a Mean Squared Error (MSE) of *Y* for the test set.

Both methods produced robust models, with predictions that closely match actual house prices.

## How to Run This Project

1. Clone the repository:
   ```bash
   git clone <https://github.com/vamsi51080/HousePricePrediction/>
   
   ```

2. Download the dataset used in the project [here](<!wget https://nkb-backend-otg-media-static.s3.ap-south-1.amazonaws.com/otg_prod/media/Tech_4.0/AI_ML/Datasets/house_price_prediction.csv>) and place it in the root directory.



## Why This Project Matters

Predicting house prices has significant real-world applications in real estate, mortgage lending, and economic forecasting. By building this project from scratch, I gained a deep understanding of how machine learning algorithms can be applied to solve complex regression problems.

This project is a practical showcase of my skills in:
- Data Preprocessing and Cleaning
- Machine Learning Model Development
- Model Evaluation & Performance Tuning
- Python and Machine Learning Libraries

If you’re looking for someone with strong analytical thinking, problem-solving abilities, and hands-on machine learning experience, I would love to connect!
