# Breast-Cnacer-classification-by-Machine-Learning
<br>
Analyzed the data of 569 patients & classified their cancer type by using Logistic Regression.
<br>
<br>
According to the dataset samples collected by biopsy method namely Fine needle aspiration.
<br>
<br>
![Fine needle aspiration](https://github.com/Akshay3190/Breast-Cnacer-classification-by-Machine-Learning/assets/149465028/de4ec992-6ae6-446d-a4c7-a8e6de0d2249)
<br>
<br>
Samples tested & divided into 2 cancer types, one is Benign & other is Malignant.
![benign-tumors-vs-cancerous-tumors](https://github.com/Akshay3190/Breast-Cnacer-classification-by-Machine-Learning/assets/149465028/afa67223-5fd1-4571-a104-067074f9262d)
<br>
<br>
We need to train the model with Logistic regression & run accordingly so that we can callsify the new samaples between these 2 cancer types.
<br>
Work flow of the project will be as follows-
<br>
<br>
<img width="960" alt="work flow" src="https://github.com/Akshay3190/Breast-Cnacer-classification-by-Machine-Learning/assets/149465028/9ac81825-796a-4012-a765-efb94b566aa9">
<br>
<br>
Libraries we used for the Processing the data-
<br>
<br>
1-Numpy
<br>
2-Pandas
<br>
3-Sikit learn
<br>
<br>
Categorized the data into 2 sectors like 'x' for the patient's entire health factors & 'y' for 'lable' that is as the classification of cancer type.
<br>
<br>
Splitting data into train & test-
<br>
<br>
Stratify-
<br>
<br>
The stratify parameter asks whether you want to retain the same proportion of classes in the train and test sets that are found in the entire original dataset. For example, if there are 100 observations in the entire original dataset of which 80 are class a and 20 are class b and you set stratify = True , with a .
<br>
<br>
Random State-
<br>
<br>
If you don't specify the random_state in the code, then every time you run(execute) your code a new random value is generated and the train and test datasets would have different values each time. However, if a fixed value is assigned like random_state = 0 or 1 or 42 or any other integer then no matter how many times you execute your code the result would be the same i.e., the same values in train and test datasets.
<br>
<br>
Trained model with the LogisticRegression function.
<br>
<br>
Logistic Regression-
<br>
<br>
It’s a popular classification algorithm used in ML. It's part of  the Sikit learn library  in Python. Regression is suitable for binary classification problems where the target variable has 2 classes. Logistic regression is a process of modeling the probability of a discrete outcome given an input variable. The most common logistic regression models a binary outcome; something that can take two values such as true/false, yes/no, and so on.
<br>
<br>
After checking the accuracy of both the training & test we checked the implementation of the model with new data.
<br>
Accuracy Score-
<br>
To check the accuracy of the model we used the 'accuracy score' function.
<br>
It’s a function that is a performance metric provided by sikit learn library  in Python. It is commonly used to evaluate the performance of a classification model by measuring the accuracy of its prediction.
<br>
<br>
Reshape new data-
<br>
While building the predictive system for new data we need to reshape the data that is we need to inform numpy array that we are going to predict the result for only one line of data.
