
# Sign Language Recognition

## Introduction

 The goal of this project was to build a Mechaine Learning model able to classify which letter of the American Sign Language
(ASL) alphabet is being signed, given an image of a signing hand. This project is a first step towards building a
possible sign language translator, which can take communications in sign language and translate them into written
and oral language. Such a translator would greatly lower the barrier for many deaf and mute individuals to be able
to better communicate with others in day to day interactions.










## image

![Screenshot 2022-12-06 190813](https://user-images.githubusercontent.com/115559638/205930596-767c171c-f633-4d2c-816f-4c541a04f564.png)

## Data sets
 In this sign language recognition notebook, we create a sign detector, which detects alphabets from A to Z that can very easily be extended to cover a vast multitude of other signs and hand gestures including the alphabets.
The dataset format is patterned to match closely with the the orignal MNIST. Each training and test case represents a label (0-26) for each alphabetic letter A-Z and a blank. The training data (12,844 cases) and test data (4267 cases) with a header row of label, pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. The original hand gesture image data represented multiple users repeating the gesture against different backgrounds. 


## Train data set img
![train data 191536](https://user-images.githubusercontent.com/115559638/205930757-c9f029e2-f16f-43da-89fe-af8c71120db4.png)


## CLASSIFIERS
## SVM (Support Vector Machine)

SVM falls into the category of supervised learning, and with the bonus of classification as well as regression problems. Generally, SVM draws an optimal hyperplane which classifies into different categories. In two dimensional space, To start with we plot the data points of the independent variable corresponding to the dependent variables. Then, begin the classification process from looking the hyperplane or any linear or nonlinear plane differentiated the two class at its best.




Accuracy score :0.99 


## Prediction of test data by SVM img

![Screenshot 2022-12-06 191645](https://user-images.githubusercontent.com/115559638/205930965-58d2a134-5d5a-4647-b5a4-efd7e6b6778d.png)

![test data 191818](https://user-images.githubusercontent.com/115559638/205931004-60055455-c13e-4638-97cd-8d9fb2e7346e.png)


## Authors

 @ SREE HARSHA K

