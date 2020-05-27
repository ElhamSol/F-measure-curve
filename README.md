# F-measure-curve
F-measure curves: A tool to visualize classifier performance under imbalance https://www.sciencedirect.com/science/article/abs/pii/S0031320319304479



# MNIST - Imbalanced binary classification problem
Train a CNN network to classify MNIST dataset into two classes, deciding
whether a digit in the image is greater (or equal to) or less than three (3), i.e. digit >= 2 or digit <2.
This is an imbalanced data classification problem.

## F-measre curve
I measure the performance in the F-measure space. This space allows us to visualize the global performance of the classifier over a range of decision thresholds, under different imbalance levels and the given preference between the classes.

![equation](http://latex.codecogs.com/gif.latex?F_%5Calpha%20%3D%20%5Cfrac%7B%5Cmbox%7BTPR%7D/%5Calpha%7D%7B1/%5Calpha%20&plus;%20%5Cmbox%7BFPR%7D/P%28&plus;%29&plus;%5Cmbox%7BTPR%7D-%5Cmbox%7BFPR%7D-1%7D)

For more information refer to the paper: "F-Measure Curves: A Tool to Visualize Classifier Performance Under Imbalance": https://www.sciencedirect.com/science/article/abs/pii/S0031320319304479
