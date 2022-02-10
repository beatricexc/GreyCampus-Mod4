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
