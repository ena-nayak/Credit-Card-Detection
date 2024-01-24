# Credit-Card-Detection
The dataset consists of credit card transaction data that is both fraudulent and not fraudulent. It
contains eight columns, one of which is our target, and 1,000,000 records. The target of interest
is the column labeled fraud, containing values 0 and 1. 0 indicates that the data is not fraudulent
and 1 indicates that the data is fraudulent. That said, our target column is categorical. This means
that our overall goal is to create a binary classifier. At first glance, none of the features can be
immediately disregarded. This is because none of the features purely serve identification
purposes. Three of our features of interest are numerical which are listed as
distance_from_home, distance_from_last_transaction, and ratio_to_median_purchase_price. The
four remaining features are categorical, which are repeat_retailer, used_chip, used_pin_number,
and online_order.

Due to the high volume of the dataset, the correlation of fraud and the remaining features cannot
be immediately determined; however, the goal of the project is to create a classification model
that can predict whether a credit card transaction is fraudulent or not fraudulent. It can be noted
that though many features appear relevant, a correlation to our target may not be present. In
addition, our model may need a certain combination of features to create the most accurate
prediction. To create this model, we will compare our target column, fraud, with our features of
interest and determine which columns, or combinations of columns, produces a model with the
least error. Secondly, we have learned about different classification models in class, including
logistic regression and support vector machines (SVM). We will be exploring these models to
attempt to obtain data that is as separable as possible.
