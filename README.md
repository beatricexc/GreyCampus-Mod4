# GreyCampus-Mod4

### Logistic Regression
**What** is Logistic Regression? 

LR predicts the binary outcome of a indepenent variable. It is named as *logistic* because its underlying technique is quite the same of Linear Regression. The term *logistic* is taken from the Logit function that is used in this method of classification. 

Binary:

- spam or not-spam
- benign or malignant
- fraudulent or genuine 


! decision boundry or decison stomp is the diferentiator between the 2 variables. it is in the shape of S (sigmoid curve) backed by the sigmoid function. The purpose of the sigmoid function is to return a probabilistic value.


#### Advantages of Logisitc Regression: 

- makes no assumption about dsitributions of classes in feature space 
- good accuracy
- resistant of overfitting
- easily extended to mutliple classes (types of logistic regression : binary 0|1 and multi-linear function eg. cars, boats, bikes)
- natural probabilistic view of classes
- quick to train 


#### Disadvantages of Logistic Regression: 
- linear decision boundry
- the range of the values has to be between 0 and 1 
- it uses the cost function called sigmoid curve/function 
- sigmoid function formula 

                 y = 1/ 1+e - ^x

**Assumptions** 
- outcome is binary 
- there is no influential value
- there is no inter-correlation

##### What is the Logit Function? 

**Logit Function** is simply the logarithm of the odds: log(x) = log(x/1-x))

The value of the logit function heads towards infinity as p approaches 1 and towards negative infinity as it approaches 0


### Decision Trees
Are used to visually and explicitly represent decisions and decision making. 

- a decision tree is built upside down with its root at the top.
- it has internal nodes
- and branches (edges)
- leafs, also knows as terminals
- prunning = when one side of the tree is heavy (biased) we cut off branches to ensure that the tree is symetrical 
**Greedy Approach** 
A greedy algorithm is a simple, intuitive algorithm that is used in optimization problems. The algorithm makes the optimal choice at each step as it attempts to find the overall optimal way to solve the entire problem (Wiki)

Entropy- E = homogenity of the data 
Entropy is used to measure disorder in the data set or how mixed a column using values between 0 and 1. If the data has equal parts of 1 and 0, then the entropy is 1. If the data consists only of 1, then the entropy is 0.

![image](https://user-images.githubusercontent.com/72341578/153506038-4a267fa1-a62b-4e42-bb6c-9589d702ac67.png)

Information Gain, IG 
Has to do with the increase or dicrease (variation) in entropy.

![image](https://user-images.githubusercontent.com/72341578/153506324-720f83be-1010-4409-b58b-1247e7a5bcf9.png)

where T = target column
A = the variable column we are splitting on
V = each value in A
