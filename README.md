# MNIST-Project-Classification-ML-Model
using the MNIST dataset, which is a set of 70,000 small images of digits handwritten by high school students and employees of the US Census Bureau

The task basically was to  build a model that classifies handwritten digits, given the handwritten images.
Each image is labeled with the digit it represents. 

The Modeling phase is split into two parts. In the first part,  I simplify the problem and train a model to predict one digit – for example the number 5. This “5-detector” is an example of a binary classifier, capable of distinguishing between two classes, 5 and not-5. In the second part, I explored multiclass classifiers that predicts all classes.

In case of predicting the classes “5” and “not 5”, the problem is binary classification problem. 
In case of predicting all classes, the problem is a multiclass classification problem.  

In selecting a performance measurement;
I employed different performance matrices:
**Classification Accuracy 
**Confusion Matrix 
**Precision and Recall TradeOff
**F1 Score 
I am  curious to see how the MNIST dataset will perform on such a model.  
