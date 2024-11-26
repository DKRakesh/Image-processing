# Image-processing
image_processing

The code performs hyperparameter tuning of a Convolutional Neural Network (CNN) for sentiment analysis using a genetic algorithm.
It uses the IMDB dataset for sentiment classification (positive/negative).
The genetic algorithm optimizes hyperparameters like the number of filters, kernel size, and dense layer sizes.
The fitness function of the genetic algorithm considers accuracy, precision, recall, and F1-score.
The best model with optimized hyperparameters is then trained and evaluated on the test set.
