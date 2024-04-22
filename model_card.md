# Model Card

See the [example Google model cards](https://modelcards.withgoogle.com/model-reports) for inspiration. 

## Model Description

**Input:** Describe the inputs of your model 

**Output:** Describe the output(s) of your model

**Model Architecture:** Describe the model architecture you’ve used

The model aims to predict lead conversion likelihood for X Education using various customer attributes. It assigns a lead score 0 or 1 to each lead (1 having high probability of conversion and 0 having low probability of conversion), indicating the probability of conversion, enabling prioritization of leads by the sales team.

## Performance

Decision Tree Classifier: Achieved the highest performance with an accuracy score of 80.3% on the validation set.
Random Forest Classifier: Yielded an accuracy score of 77% on the validation set.
AdaBoost Classifier: Showed a performance close to the Decision Tree Classifier, with an accuracy score of 79% on the validation set.

## Limitations

Dependency on Historical Data: The model's performance may be limited by changes in customer behavior or market dynamics not captured in the training data.
Interpretability: Decision tree-based models offer high performance but may lack interpretability compared to simpler models like logistic regression.
Overfitting: Decision tree-based models are prone to overfitting, especially with complex datasets, which may lead to poor generalization on unseen data.

## Trade-offs

Decision Tree Classifier: Offers high performance but may sacrifice interpretability.
Random Forest Classifier: Provides robustness against overfitting but may be computationally expensive.
AdaBoost Classifier: Balances between model complexity and performance but may require tuning of hyperparameters.
