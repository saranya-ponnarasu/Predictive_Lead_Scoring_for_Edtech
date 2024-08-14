# Summary

This analysis aims to predict which leads will convert to customers for an edtech company using a dataset containing lead-related features. Below is a concise summary of the findings and actions taken:

### Objective:
The goal is to classify whether a lead will convert based on various features, such as Lead Source, Occupation, email subscription, last activity, and time spent on site.

### Dataset Overview:
- Features:
    - Includes occupation, country, city, email subscription status, last activity, and time spent on site.

- Key Statistics:
  - The dataset reveals varying engagement levels, with a notable portion of leads showing high interest.
    
### Data Cleaning:

- Encoding: Applied binary encoding and one-hot encoding to convert categorical variables into numeric format.
- Train-Test Split:
    - Train Size: X (6456, 37) , y (6456,)
    - Test Size: X (2153, 37) , y (2153,)
- Addressing Class Imbalance:
  - Initial Class Distribution: Class 0 - 38%  and Class 1 - 62%.
  - Used SMOTE Algorithm to balance the classes

### Model Building:

- Logistic Regression Model: Trained and evaluated using the processed dataset.
- Performance Metrics:
  - F1 score - Accuracy: 80%
  - Sensitivity - 74%
  - Specificity - 83%

### Model Evaluation:

AUC Score: 0.90, indicating a strong ability to distinguish between converters and non-converters.
ROC Curve: Demonstrates the model's robust ability to differentiate between the two classes.

--- 
This concludes the analysis. The model shows good performance in terms of accuracy and AUC Score , aligning with the business objective of predicting lead conversions for the edtech company. Further enhancements can be made to optimize the balance between precision and recall for improved utility in practical scenarios. The model is now ready for deployment based on the identified optimal threshold.
