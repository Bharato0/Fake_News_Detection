# Fake_News_Detection
### Fake News Detection using Python and Machine learning with local Deployment

### TABLE OF CONTENT

- Introduction
- Major Problem	Technologies Used
- Purpose	Results
- Work Flow of Project	Conclusion


### What is a Fake News?

- Fake News is a news designed to deliberately spread hoaxes, propaganda, and disinformation.
- Fake News Stories usually spread through social media sites like Facebook, Twitter, Instagram, etc.
- The wide spread distribution of fake news has the potential to have highly negative effects on people and culture.

### Major Problem

- Fake news influences people's perception.
- Fake news are used as clickbait for the profit of content publishers. More clicks contributes more money to them.
- The rise of fake news has become a global problem that will impact people, culture as a whole and in general, doubt the authenticity of journalism as well.

### Purpose

- This project aims to develop a method for detecting the news stories using machine learning.
- The main goal of this project is to identify and predict whether a given news article is a fake news or not.
- We gathered our data, preprocessed the text, and translated our articles into supervised model features.
###### Delimitations: My project does not guarantee 100% accuracy.

### Work Flow of Project

1. Collection of Data
2. Pre-processing of data
3. Extract Features
4. Content Classification
5. Training the model
6. Training the classifier

### Techniques Used
#### Logistic Regression
- Logistic regression is a statistical method used for binary classification problems, where the goal is to predict the probability of a binary outcome (whether the new is fake or not) based on one or more input variables (also known as independent or predictor variables).
- It models the relationship between the input variables and the binary output variable using sigmoid function, which transforms the output of the model to a probability between 0 and 1.
#### Decision Tree Classifier 
- A decision tree classifier is a type of algorithm used for classification tasks that builds a tree-like model by recursively partitioning the data based on the input variables and their values to predict the class label of new data.
#### Gradient Bound Classifier - A gradient bound classifier is a type of machine learning algorithm used for
classification tasks. It updates a set of weights to minimize the difference between predicted and actual outcomes. The "gradient bound" term means it has a constraint that prevents the weights from becoming too large. This helps prevent numerical instability or overfitting.
#### Random Forest Classifier
- A random forest classifier is a type of machine learning algorithm used for classification tasks. It combines many decision trees to make a prediction. Each tree looks at a random subset of the data and features, which helps to prevent overfitting. The final prediction is based on the most commonly predicted class by all the trees. Random forest classifiers are accurate and can handle large and complex datasets.
 
#### Results
##### The outcome of our project is as follows:
- Logistic Regression: Out of all the test cases we have tested on the model, it gave 100 percent accuracy on trained data and more than 85% accuracy on untrained data(predicted data).
- Decision Tree Classifier: Out of all the test cases we have tested on the model, it gave 100 percent accuracy on trained data and more than 60% accuracy on untrained data(predicted data).
- Gradient Bound Classifier: Out of all the test cases we have tested on the model, it gave 100 percent accuracy on trained data and more than 70% accuracy on untrained data(predicted data).
- Random Forest Classifier: Out of all the test cases we have tested on the model, it gave 100 percent accuracy on trained data and more than 90% accuracy on untrained data(predicted data).
 
## Conclusion
- The outcome of this project shows the capability of machine learning to be fruitful in this Task. We have tried to build a model that helps in catching many intuitive indications of real and fake news. We have used multiple performance matrics.








