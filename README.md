# GoogleMachineLearningCrashCourse


Terminology

Example - data instance X
Labeled example  - (X,Y) Use to train the model
Unlabeled example (x,?) Used for making predictions on new data
Model - maps examples to y' and defined by internal parameters


Linear Regression

 y = w1x1 + w2x2 ... w?x?

 Empirical risk minimizaiton - attempt to find a model that minimizes loss. 

 Loss - penalty for bad prediction. 

 L2 - Squared loss. 

 MSE - means square error is aversage squared loss per example. 
 
 Iterate to decrease the loss with gradient descent. Gradient of loss is slope of the loss curse, which shows how close we are to minimum loss. 
 Use Optimization of learning rate(step size). If too big will miss minimum loss and if to small will take too many iteration.

Batch is the total number of examples you use to calculate the gradient in a single iteration.

 SGD - Stochastic gradient descent use batch size of 1 per iteration. often contains to much noise.

Mini-batchstochastic gradient descent - 10 - 1000 examples chosen at random. 


Learn NP and Panda.
Learn TF tool(vaguely)

Generalization : Peril of overfitting 
- Overfitting a model will cause greater error on the other data.
- Divide data set to training set and test set. 
- Three Rules Generalization
    1. Independently and identically at random distribution. Refering to the randomness of variables.
    2. Stationary. Same distribution within data set
    3. Draw example from same distribution.

Traning and Test Data : Splitting Data
- Never train on test data.     
- 8:2 split on Train and Test Data

Validation Set: Another Partition
- Use another partition called validation set to alter learning rate and epoches. 



