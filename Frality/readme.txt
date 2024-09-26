Title: Grip Strength and Frailty Study - Female Participants

Data Information: Hand grip strength measured using a dynamometer.

Data Description:
- Height: Participant height in inches.
- Weight: Participant weight in pounds.
- Age: Participant age in years.
- Grip Strength: Hand grip strength measured in kilograms using a dynamometer.
- Frailty: Qualitative indication of frailty. Y = frail, N = not frail.


Grip Strength and Frailty Study

Exploratory Data Analysis (EDA)
-Summary Statistics:
Descriptive statistics were generated for each variable, providing insights into the mean, standard deviation, and distribution.
-Correlation Analysis:
A correlation matrix was calculated to assess relationships between numeric variables.
Notable correlations included:
-Grip Strength and Frailty: Lower grip strength is associated with higher frailty scores.
-Age and Grip Strength: Grip strength tends to decrease with age.
Visualizations:
-Correlation Heatmap: Visual representation of correlations among variables.
-Scatter Plot: Illustrates the relationship between grip strength and age, with frailty status indicated by color.
-Box Plot: Compares grip strength between frail and non-frail participants, showing that frail individuals generally have lower grip strength.

Logistic Regression Modeling:
Model Overview:
A logistic regression model was developed to predict frailty based on grip strength and age.
Model Evaluation:
The model achieved an accuracy of 80% on the test set, indicating a good fit.
-Confusion Matrix: Displays true positives, true negatives, false positives, and false negatives.
-Classification Report: Provides precision, recall, and F1-score for frail and non-frail classifications:
-Frail Class Precision: 67% (proportion of positive identifications that were actually correct).
-Frail Class Recall: 100% (proportion of actual positives that were identified correctly).