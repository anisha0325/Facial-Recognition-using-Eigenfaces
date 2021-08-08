# Facial-Recognition-using-Eigenfaces

The problem is of facial recognition wherein we compare characteristics of a face image to that of
face images of known individuals. The approach implemented treats this problem of face recognition
as two-dimensional rather than requiring three-dimensional geometry by taking advantage of the fact
that faces are generally upright, and may thus be described in terms of two-dimensional characteristics.
The method used is Eigenfaces, where we project the images into a low-dimensional feature space using
Principal Component Analysis.

The Yale Face Database has been used to carry out the experimentation. It contains a total of 165
images of 15 different persons (classes). Each of these persons have 11 distinct images which differ in either
expression or lighting conditions. The images are gray scale having dimensions 320 x 243. For training,
150 images from this data set were used. For testing, the remaining 15 images of 15 different people were
kept aside. This test set of 15 face images had normal expressions. Along with this, the test set was fed
with one non-face image not in the Yale Face Database and two non-face images. Our goal was to detect
the accuracy with which the model could detect the known face images and its behaviour when tested on
face images not in the training set and non-face images.

Out of the 15 test images from the data set, the model could identify 14 images correctly. From the 1 unknown face image and 2 non-face images not in the dataset, the algorithm correctly identifies 1 inknown face image and 1 non-face image.

References
[1] M. Turk and A. Pentland, \Eigenfaces for Recognition," J. Cognitive Neuroscience, vol. 3, no. 1, 1991.
[2] http://vision.ucsd.edu/content/yale-face-database
