# Logistic-Regression---Fraud-prevention
Logistic Regression is a statistical method used to predict the probability of a binary dependent variable (i.e., with two possible outcomes, such as yes/no, 0/1, true/false) and one or more independent variables. Unlike linear regression, which predicts continuous values, logistic regression predicts probabilities that can be transformed into one of the two possible categories.

# Interpretation of AUC

AUC = 1: The model is perfect and can distinguish between the classes 100% of the time.
AUC = 0.5: The model has no discriminative ability and is only getting it right by chance (like a random model).
AUC < 0.5: The model is performing worse than a random model, suggesting something is fundamentally wrong with the model or the data.
AUC-ROC is useful for comparing models as it helps compare the performance of different models, especially in problems with imbalanced classes.

# Confusion Matrix: As the name suggests, it can sometimes be confusing to understand haha. Definitions:

True Positives (TP): Number of cases where the model correctly predicted the positive class.
False Negatives (FN): Number of cases where the model predicted the negative class, but the actual class was positive.
False Positives (FP): Number of cases where the model predicted the positive class, but the actual class was negative.
True Negatives (TN): Number of cases where the model correctly predicted the negative class.
