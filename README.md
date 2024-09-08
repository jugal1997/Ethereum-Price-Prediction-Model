# Ethereum-Price-Prediction-Model

Ethereum Price Prediction using Neural Networks

Project Description:
This project aims to predict the future price of Ethereum using a neural network model. A Long Short-Term Memory (LSTM) network is developed and trained to capture the temporal dependencies inherent in cryptocurrency price data.

Technologies:

Python
TensorFlow
NumPy
Pandas
Matplotlib
Data:

Historical Ethereum price data.
Methodology:

Data Preprocessing:

Cleaned and prepared the dataset, handling missing values and outliers.
Normalized the price data to a suitable range.
Created time-lagged features to incorporate historical price information.
Model Development:

Implemented an LSTM-based neural network architecture.
Used TensorFlow to construct and train the model.
Applied L1 regularization to prevent overfitting and improve generalization.
Incorporated early stopping to terminate training when performance plateaus.
Model Evaluation:

Evaluated the model's performance using the Symmetric Mean Error (SME) and Root Mean Squared Error (RMSE).
Results:

Achieved a SME of 0.43 and RMSE of 0.66, indicating a significant reduction in error rates.
Demonstrated improved forecasting accuracy compared to baseline models.
Future Work:

Explore other neural network architectures, such as GRU or Transformer, for potential performance improvements.
Incorporate additional features, such as trading volume or sentiment analysis, to enhance prediction accuracy.
Experiment with different optimization techniques and hyperparameter tuning to further refine the model.

