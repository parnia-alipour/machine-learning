
![image2](https://user-images.githubusercontent.com/74038190/221352989-518609ab-b4d1-459e-929f-a08cd2bd9b3c.gif)


## Machine Learning
___
 In this project, we work with various machine learning algorithms and learn how to build an artificial intelligence model. The project includes 10 diverse algorithms applied to different datasets, featuring methods such as :

1. `k-nearest neighbors`
2. `logistic regression`
3. `Svm`

*  Artificial intelligence to determine whether it will rain today or not ==== (KNeighborsClassifier)--[weather.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/weather.ipynb)

*  Artificial intelligence for music genre recognition==== (Random Forest)--[music.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/music.ipynb)
**In this project, I ran into a problem where the evaluation metrics were showing very high scores, but the model couldn't predict the genres correctly in practice. After some re-evaluation and analysis, I realized there was a data leakage issue: the target column hadn't been fully separated from the training data. So the model was basically just "seeing" the labels instead of actually learning the features. I fixed this by properly isolating the target, which led to a real and reliable prediction.**
*  This algorithm is designed with the aim of analyzing customer personality and segmenting them for better marketing for employees and investors====(Hierarchical algorithm)--[shape.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/music.ipynb)

* Artificial intelligence to determine whether people are male or female based on their voices===(GaussianNB)--[voice.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/voice.ipynb)

*  Implementation of the same customer personality analysis and segmentation for better marketing, but this time with SciPy===[scipy_hierarchiacal.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/scipy_hierarchiacal.ipynb)

*  Iris flower clustering====(k-means)--[iris.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/iris.ipynb)
*  Artificial intelligence for estimating house prices based on location, number of rooms, and so on====Linear regression--[home_California.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/home_California.ipynb)

*  Artificial intelligence for sentiment analysis===(SVM)--[ehsasat.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/ehsasat.ipynb)

*  Artificial intelligence for diabetes diagnosis===(Decision Tree)--[diabetes.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/diabetes.ipynb)
**In this project, I noticed that the model was predicting every new data point as "diabetic"! After some analysis, I realized the model was "Overfitting" and failed to predict new data correctly. The most important thing I learned in this project was: never trust a perfect score of 1.0 until I have tested it thoroughly.**


*  Artificial intelligence for diagnosing heart disease===(Logistic Regression)--[heart_disease.ipynb](https://github.com/parnia-alipour/machine-learning/blob/master/heart_disease.ipynb)
**In this project, I noticed that the heart data was acting completely opposite to what was provided in the data description; it was predicting healthy people as sick and sick people as healthy. But how did I find out? From "Cholesterol" and "Oldpeak," because these are the most important criteria for heart disease and these two columns mostly define whether a person is sick or not**








 This project also includes two clustering algorithms that help us better understand and learn the other machine learning models.

##  All the projects are written in both Persian and English.

Please take a look at Music.ipynb first.👩🏻‍💻🙏🏻

[read this](https://parnia-alipour.github.io/machine-learning/)

---
___

```python

from sklearn.linear_model import LogisticRegression

model=LogisticRegression()
model=model.fit(x_train,y_train)

predictions = model.predict(x_test)

```


!['image'](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)       !['image3'](https://img.shields.io/badge/machine%20learning-purple)      !['image4'](https://img.shields.io/github/commit-activity/m/parnia-alipour/project/master) !['image5'](https://img.shields.io/github/contributors/parnia-alipour/project  
)




