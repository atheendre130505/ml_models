# ml_models
hardcoding ml models to know what makes them tick and playing around with them to get even deeper and broader knowledge.
includes: linear regression, logistic regression, polynomial regression, neural networks, CNN, RNN, Transformers

observations for linear regression: 0.025 learning rate, works well, 200 epochs is good enough for data that doesnt require much accuracy, for feature scaling implement standard(z score) or robust(x-median/iqr)(if outliers exists), and the best cost function is huber as it combines both mean squared(mse) and mean absolute(mae).
