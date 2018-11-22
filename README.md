# ReflectionExperiments

### Experiment on Classicial Machine Learning Models
Our architecture is closely designed as Adaboost. To show a possible for the combination of neural networks; the first step is to prove it using classicial learning methods. The benefits of testing on machine learning models are straight forward. 

1. It's easier to perform analysis based on classicial machine learning models rather than neural networks. In fact, the power of Reflection came from the fact that it satisfy the architecture of an ensemble method. We need a further investigation. 

2. Starting from the theory and experiment result in statistical learning method can help us better to extend to a neural network. 

#### Links to ongoing experiments
[Reflection on Logistic Regression on MNIST.](https://colab.research.google.com/drive/1c2f6P50Cb6KJV2c3lLNhbQwgfaBfs-50)

k = 1
|TaskClf|Clf|Accuracy TaskClf|Accuracy Reflection|Accuracy Original|Accuracy Specialist|
|-------------|--------|-----|----|-----|-----|
|Decision Tree|Logistic|84.3%|84.08%|83.97%|40%|
|Logistic|Logistic|%|%|%|%|
|Naive Bayes|Logistic|%|%|%|%|
|Adaboost|Logistic|%|%|%|%|

k = 2
|TaskClf|Clf|Accuracy TaskClf|Accuracy Reflection|Accuracy Original|Accuracy Specialist|
|-------------|--------|-----|----|-----|-----|
|Decision Tree|Logistic|78.3%|86.3%|89%|30%|
|Logistic|Logistic|87.7%|89.6%|89.6%|30%|
|Naive Bayes|Logistic|7.3%|30%|89.6%|30%|
|Adaboost|Logistic|82.3%|83.5%|83.5%|30%|
|NN|Logistic|%|%|%|%|


Logistic Regression as a task classifier will fail to predict correctly. It will always predict the 0. 
Naive Bayes also fails to perform Reflection in our case. 
