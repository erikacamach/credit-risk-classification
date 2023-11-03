# credit-risk-classification


#Overview#

In this analysis, we aimed to assess a dataset containing historical lending data from a peer-to-peer lending service. Our goal was to develop a model capable of determining borrowers' creditworthiness based on various financial factors, such as loan size, interest rate, income, debt-to-income ratio, and more.

We observed an imbalance in the dataset, with 75,036 healthy loans (label 0) and 2,500 high-risk loans (label 1). The analysis followed several stages: data pre-processing (cleaning and preparation), model training, and model evaluation.

#Results#

Machine Learning Model 1:

*Accuracy: 18679 true positives and 558 true negatives.
*Precision: Better at predicting healthy loans (precision 1) than high-risk loans (precision 0.87).
*Recall: Better at identifying healthy loans (recall 1) than high-risk loans (recall 0.89).
*Support: Indicates an imbalance in the training data (18759 healthy loans vs. 625 high-risk loans).

Machine Learning Model 2:

*Accuracy: 55945 true positives and 55954 true negatives.
*Precision: Equally effective for both healthy loans (precision 0.99) and high-risk loans (precision 0.99).
*Recall: Equally effective for both healthy loans (recall 0.99) and high-risk loans (recall 0.99).
-Support: Indicates a balanced dataset (56277 healthy loans vs. 56277 high-risk loans).

#Summary#

In summary, 'Machine Learning Model 2' is recommended due to its balanced scores and improved performance after resampling. With a balanced dataset, it can effectively predict loan risks, categorizing them as healthy or high-risk loans.
