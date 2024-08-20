# Activity I: Analysis of Regularization and Classification Techniques

Select a dataset (the Iris dataset is not accepted) to develop the following points:

### a. L1 and L2 Regularization in Classification Tasks
Explain in detail how L1 and L2 regularization work in classification tasks, and how they are implemented in sklearn.

### b. Cross-Entropy Loss in Logistic Regression
Research cross-entropy loss and how it is implemented in logistic regression. Develop the mathematical derivation to understand how gradient descent is applied to this loss function.

### c. multi_class Parameter in Logistic Regression
Explain the options for the multi_class parameter in the logistic regression classifier and how they function in sklearn.

### d. solver='sag' in Logistic Regression
Explain the use of solver='sag' in sklearn's logistic regression.

### e. SGDClassifier Class in sklearn
Explain the SGDClassifier class in sklearn.

### f. Encoding Categorical Data
Explain three different ways to encode categorical data, and what their advantages and disadvantages are.

# Realization

For the solution of the activity, a **[Dataset](https://www.kaggle.com/datasets/lightningforpython/spam-or-not?select=spam.csv)** from Kaggle is initially chosen, which contains two categories of messages: "ham" and "spam" with 5000+ rows.
The procedure is divided into two parts.

EDA, which can be found at **[EDA Notebook](https://github.com/RJuanJo/IA_Activities/blob/main/1stHomework/notebooks/eda.ipynb)** and provides good insights into the nature of the data and how the data is organized within the dataset.

The second part is located at **[Model Training Notebook](https://github.com/RJuanJo/IA_Activities/blob/main/1stHomework/notebooks/classification_model.ipynb)**, where the requested assignments are addressed, and it moves on to the model training for the data. 

For the activity, the following libraries are required:
´´´
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations and array manipulation.
- **seaborn**: For data visualization.
- **matplotlib**: For creating static, animated, and interactive visualizations.
- **collections**: For specialized container datatypes.
- **sklearn**: For machine learning, specifically for model training and evaluation.
- **wordcloud**: For generating word clouds from text data.
- **re**: For working with regular expressions.
´´´
