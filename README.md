# Sonar_RockVs.Mine_predictor
This is my first Project on Machine Learning .
# Overview
 Submarine uses a sonar that sends sound signal and reviews switch back of the signal. So, this signal is then processed to detect whether the object is mine or just a rock in the ocean.
These sound waves can travel for hundreds of miles under water, and can retain an intensity of 140 decibels as far as 300 miles from their source.

Collection of sonar data: It is possible to run an experimental setup in which sonar is used to send and receive signals. There is a big difference between signals from mines and rocks. Because mines are made of metal.
So the data we collect is nothing more than sonar data from rocks and metal cylinders.
We then take this sonar data and transfer it to our machine learning model.
Our model predicts whether the product is metal or rock.

# Implementation
The problem uses Logistic Regression to model the binary dependent  variable in dataset as the problem is based on Binary classification.

#### Dataset: 
I got sonar data in .csv format from UCL Repository by Connectionist Bench.It has total of 60 feature columns and 1 label column and 208 rows of instances.

#### WorkFlow:
![aaa](https://github.com/aShutOSh0139/Sonar_RockVs.Mine_predictor/assets/111175990/5aefca54-e2dd-4534-ad20-893b61bf7c97)


![bbb](https://github.com/aShutOSh0139/Sonar_RockVs.Mine_predictor/assets/111175990/1151e817-9475-42f3-a927-180150a57e2f)

# Acknowledgements
---->[Sonar Rock vs Mine Prediction](https://youtu.be/fiz1ORTBGpY)<br>
---->[Prediction of Underwater Sonar Targets](https://ijarcce.com/wp-content/uploads/2022/07/IJARCCE.2022.11793.pdf)<br>
---->[medium.com](https://medium.com/catalysts-reachout/interesting-machine-learning-projects-rock-vs-mine-prediction-32419954a6a3#:~:text=Because%20mines%20will%20be%20made,it%20is%20just%20a%20rock.)
