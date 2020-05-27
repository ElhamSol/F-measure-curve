# F-measure-curve
F-measure curves: A tool to visualize classifier performance under imbalance https://www.sciencedirect.com/science/article/abs/pii/S0031320319304479



# MNIST - Imbalanced binary classification problem
Train a CNN network to classify MNIST dataset into two classes, deciding
whether a digit in the image is greater (or equal to) or less than three (3), i.e. digit >= 2 or digit <2.
This is an imbalanced data classification problem.

## F-measre curve
I measure the performance in the F-measure space. This space allows us to visualize the global performance of the classifier over a range of decision thresholds, under different imbalance levels and the given preference between the classes.


<img src="https://render.githubusercontent.com/render/math?math= F_\alpha = \frac{\mbox{TPR}/\alpha}{1/\alpha + \mbox{FPR}/P(+)+\mbox{TPR}-\mbox{FPR}-1} ">

For more information refer to the paper: "F-Measure Curves: A Tool to Visualize Classifier Performance Under Imbalance": https://www.sciencedirect.com/science/article/abs/pii/S0031320319304479
