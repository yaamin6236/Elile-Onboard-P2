In this project, several enhancements were made to improve the performance and readability of the LSTM model for predicting solar energy. The key changes include:

Data Sorting: The dataset is now sorted in ascending order by year, month, day, and hour columns to maintain the temporal structure, which is crucial for time series forecasting.

Normalization and Data Scaling: A normalization function was added to scale the features between 0 and 1, ensuring all input features are on a similar scale.

Model Checkpointing: The ModelCheckpoint callback was introduced to save the best model during training based on validation loss, helping to preserve the best performing model.

Hyperparameter Tuning: A grid search approach was implemented to optimize hyperparameters such as initialization methods, epochs, batch sizes, and optimizers. This systematic search helps in finding the best combination of parameters for the model.

Visualization: Added a plot to visualize the actual vs. predicted solar energy values, providing a clear visual representation of the model's performance.

My final loss from training reached 0.01850 compared to the original 0.0284
