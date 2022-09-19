# Feature-Selection-on-Salary-Data

### Feature Selection

Feature selection is primarily focused on removing non-informative or redundant predictors from the model. When you are done creating hundreds of thousands of features, it’s time to select a few of them. Well, we should never create hundreds of thousands of useless features. Having too many features pose a problem well known as the curse of dimensionality. If you have a lot of features, you must also have a lot of training samples to capture all the features.

### Step for forwarding Selection
- Start with the empty feature set
- Try the remaining feature
- Estimate classification/regression error for adding each feature in the model
- Select a feature that gives maximum improvement
- Stop when there is no significant improvement

### Step for Backward Selection

- Start with a complete feature set
- Try the remaining feature
- Estimate classification/regression error for adding each feature in the model
- Drop feature that gives less improvement
- Stop when there is no significant improvement

### Step for Backward Selection

- Start with a complete feature set
- Try the remaining feature
- Estimate classification/regression error for adding each feature in the model
- Drop feature that gives less improvement
- Stop when there is no significant improvement
