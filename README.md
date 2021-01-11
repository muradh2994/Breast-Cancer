# Breast Cancer

Wisconsin (Diagnostic) Data Set is used to predict Breast Cancer using basic Artificial Neural Network.
Dataset Source : https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

# Data Set Information:
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. A few of the images can be found at [Web Link]

Separating plane described above was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree. Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

# Attribute Information:
1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

# Model Description :

For this, I have used Sequential model in Keras which is a high-level Neural Networks API built on top of low level neural networks APIs like Tensorflow and Theano.
As it is high-level, many things are already taken care of therefore it is easy to work with and a great tool to start.

# Parameters :

Train-Test Split - 70:30
No.of Hidden layers - 2
Initializer - glorot_uniform
Activation function - tanh
Dropout - 30% on both layers
Optimizer - Adam
Loss function - Cross-entropy


Overall Accuracy obtained is 97%

