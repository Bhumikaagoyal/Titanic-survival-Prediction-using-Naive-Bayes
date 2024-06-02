# Titanic-survival-Prediction-using-Naive-Bayes
The Titanic Survival Prediction uses Naive Bayes algorithm to predict the probability of passengers surviving the sinking of the RMS Titanic in 1912, using features like class, age, gender, and socio-economic indicators.
Naive Bayes operates under the assumption of feature independence, meaning it assumes that the presence of one feature is unrelated to the presence of any other feature. Despite its simplicity, Naive Bayes has proven to be effective in various classification tasks, particularly in scenarios with relatively small datasets and when feature independence assumption holds reasonably well.

The process of building a Titanic Survival Prediction model using Naive Bayes typically involves the following steps:

Data Preprocessing: This involves cleaning the dataset, handling missing values, and encoding categorical variables. Additionally, feature scaling or normalization may be performed to ensure all features contribute equally to the model.

Feature Selection: Identifying the most relevant features that strongly correlate with survival outcomes can enhance the model's predictive accuracy. Factors such as passenger class, gender, age, and potentially familial relationships aboard the Titanic may significantly influence survival probabilities.

Model Training: The Naive Bayes algorithm is trained on a subset of the dataset, where it learns the probability distributions of the features given each class label (survived or not survived). Despite its simplicity, Naive Bayes tends to perform well with small to moderate-sized datasets.

Model Evaluation: The trained model is evaluated using techniques such as cross-validation or a separate validation dataset to assess its performance metrics like accuracy, precision, recall, and F1-score. These metrics provide insights into how well the model generalizes to unseen data.

Prediction: Once trained and validated, the model can be deployed to predict the survival probabilities of passengers in unseen data. By inputting the relevant features of an individual passenger, the model computes the probability of survival based on the learned probability distributions.

Interpretation and Insights: The final step involves interpreting the model's predictions and extracting insights into factors that contribute to higher survival chances. This analysis can aid in understanding the demographics or characteristics of passengers who were more likely to survive the Titanic disaster.

In summary, the Titanic Survival Prediction using Naive Bayes algorithm serves as a valuable tool for understanding historical events like the Titanic disaster through the lens of data analysis and machine learning, shedding light on the factors that influenced passenger survival outcomes.





