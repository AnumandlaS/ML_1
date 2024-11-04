# ML_1:
This project aims to understand just the basics of logistic regression, a concept in ML.
Logistic regression is a commonly used technique for solving binary classification problems.
- Whether we're solving a regression problem using linear regression or a classification problem using logistic regression, the workflow for training a model is exactly the same:
1. We initialize a model with random parameters (weights & biases).
2. We pass some inputs into the model to obtain predictions.
3. We compare the model's predictions with the actual targets using the loss function.
4. We use an optimization technique (like least squares, gradient descent etc.) to reduce the loss by adjusting the weights & biases of the model
5. We repeat steps 1 to 4 till the predictions from the model are good enough.</br>
   
**Training set** - used to train the model, i.e., compute the loss and adjust the model's weights using an optimization technique.</br>
**Validation set** - used to evaluate the model during training, tune model hyperparameters (optimization technique, regularization etc.), and pick the best version of the model.</br>
**Test set** - used to compare different models or approaches and report the model's final accuracy. For many datasets, test sets are provided separately.</br>
As a general rule of thumb you can use around 60% of the data for the training set, 20% for the validation set and 20% for the test set. If a separate test set is already provided, you can use a 75%-25% training-validation split.</br>
