Support Vector Machine (SVM)
Support Vector Machine (SVM) is a supervised machine learning algorithm primarily used for classification and regression tasks. It is based on the idea of finding a hyperplane that best separates the data into classes.

Key Concepts:

1. Hyperplane
A hyperplane is a decision boundary that separates data points in an
n-dimensional space. For example:
In a 2D space, it's a line.
In a 3D space, it's a plane.
In higher dimensions, it’s called a hyperplane.

3. Margin
The margin is the distance between the hyperplane and the closest data points (on either side of the hyperplane). These closest points are called support vectors.
Objective: Maximize the margin to ensure better generalization of the model.

4. Support Vectors
These are the data points closest to the hyperplane. They influence the position and orientation of the hyperplane. Removing a support vector changes the hyperplane.

5. Linear vs. Non-linear
SVM can handle both linearly separable and non-linearly separable data. For non-linear data, it uses a kernel trick to map the data into a higher-dimensional space.
