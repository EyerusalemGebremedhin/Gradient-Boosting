Titanic Gradient Boosting Model

The goal of this project is to train a machine learning model called Gradient Boosting using historical data. Once the training is complete, we use the model to test its ability to predict survival outcomes on an unseen passenger dataset.

The notebook file named trained gradient boosting contains the code used to train the machine learning model. The file named final predictions is the final spreadsheet containing all the resulting survival predictions.

The model works by first filling in missing passenger ages and ticket prices with the middle median value. Then it analyzes factors like passenger class, sex, age, family members, and ticket costs to find patterns. Finally, it uses a Gradient Boosting Classifier to decide whether each passenger survived or not.
