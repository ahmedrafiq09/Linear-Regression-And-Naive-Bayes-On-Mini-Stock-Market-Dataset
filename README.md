## Market Direction Prediction Analysis

### Overview
This project evaluates logistic regression and Naive Bayes classification techniques for predicting market direction using the Smarket dataset. This dataset comprises percentage returns on 1,250 days of the S&P 500 stock index, along with Lag1-Lag5, Volume, Today, and Direction.

### Logistic Regression
- **Model Fitting**: Trained logistic regression model with Lag1-Lag5 and Volume as features to predict market direction (Up or Down). Extracted coefficients, standard errors, and p-values for feature significance.
- **Association with Lag1**: Analyzed the coefficient related to Lag1 to determine its influence on market direction.
- **Predicted Probabilities**: Mapped predicted probabilities to class labels (Up or Down) using a threshold. Evaluated likelihood of market growth.
- **Performance Metrics**: Computed confusion matrix and metrics like accuracy, precision, recall, and F1-score to assess model performance.

### Naive Bayes Classifier
- **Data Partitioning and Fitting**: Split dataset, fitted Gaussian Naive Bayes model to training sample.
- **Model Characteristics**: Examined distinct classes, prior probabilities, and feature statistics per class.
- **Predictions and Confusion Matrix**: Generated predictions and constructed confusion matrix for test set evaluation.
- **Performance Evaluation**: Calculated accuracy, precision, recall, and F1-score for model assessment.

### Conclusion
This analysis provides insights into the effectiveness of logistic regression and Naive Bayes models for market direction prediction. By combining qualitative and quantitative assessments, it offers valuable guidance for financial decision-making.
