# Human-Activity-Recognition
HUMAN ACTIVITY RECOGNITION WITH SMART PHONES
Recognizing human activities from temporal streams of sensory data observations is a very important task on a wide variety of applications in context recognition. Human activities are hierarchical in nature, i.e. the complex activities can be decomposed to several simpler ones. Human activity recognition is the problem of classifying sequences of accelerometer data recorded by pre-installed sensors in smart phones into known well-defined movements to make it ready for predictive modelling.

Question:
Perform activity recognition on the dataset using a hidden markov model. Then perform the same task using a different classification algorithm (logistic regression/decision tree) of your choice and compare the performance of the two algorithms

Problem statement:
Classify the Human activities based on data collected from smartphones. The activities include

walking
walking upstairs
walking downstairs
sitting
standing
laying.
The dataset contains various features such as accelerometer and gyroscope reading from the smart phone.

Dataset:
The Human Activity Recognition database was built from the recordings of 30 study participants performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.
It contains 561 features,which are the result of preprocessing the accelerometer and gyroscope readings from the smartphone with 6 activities as mentioned above.
The dataset contains 7352 samples for training and 2947 samples for testing.
Feature selection:
Since the dataset contains a large number of faetures ,we need to perform feature selection to reduce the number of features to improve the performance of the model.

Procedure
- Importing Libraries
- Data Preprocessing
- Store Feature Matrix in x and Target in Vector y
- Splitting data into training and testing
- Hidden Markov Model
- Use Logistic Regression
- Random forest Classifier
- Evaluation
- Feature selection
- Filter Method
- Wrapper Method
