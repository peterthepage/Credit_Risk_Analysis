# Credit_Risk_Analysis
## Overview
Credit risk is a difficult classification problem because it is so unbalanced. This is because good loans greatly outnumber risky loans. They way to work around this was to create a model, and then evaluate and train the models. Imbalanced-learn and scikit-learn libraries were used to build models.
## Results
* Naive Random Oversampling - Balanced Accuracy = .629 Precision is low for high risk loans and is high for low-risk loans.
* ![pic1](https://github.com/peterthepage/Credit_Risk_Analysis/blob/main/Pictures/Capture1.PNG)
* Smote Oversampling - Balanced Accuracy = .628 Precision is low for high risk loans and high for low-risk loans.
* ![pic2](https://github.com/peterthepage/Credit_Risk_Analysis/blob/main/Pictures/Capture2.PNG)
* Undersampling - Balanced Accuracy = .628 Precision is low for high risk loans and high for low-risk loans.
* ![pic3](https://github.com/peterthepage/Credit_Risk_Analysis/blob/main/Pictures/Capture3.PNG)
* Combination Under-Over Sampling Balanced Accuracy .620 Precision is low for high risk loans and high for low-risk loans.
* ![pic4](https://github.com/peterthepage/Credit_Risk_Analysis/blob/main/Pictures/Capture4.PNG)
## Summary
The first four models the accuracy score is nat high and the recall is low as well. I'd recommend the ensemble classifiers because it's accuracy was higher than the first four models. The easy ensemble had the highest accuracy score and a solid balance of precision and recall scores.
