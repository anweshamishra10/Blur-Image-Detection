# Blur-Image-Detection

QUESTION:

Image quality detection has always been an arduous problem to solve in computer vision.
In this assignment, you have to come up with features and models to build a classifier that will predict whether a given image is blurred.

APPROACH:

In Blur Image Detection, to detect whether an image is blurred or not, we should check the edges of the image. This can be done by using the
Laplacian method to detect the edges. After applying Laplacian, we can find the variance and maximum of the pixels of the image. Whichever 
image has more variance and maximum has sharp edges, hence it is a clear image and vice versa.

STEPS:

Step 1: Download the files from the dataset given and keep them in the C drive of your system.

Step 2: Install the following libraries using pip in cmd.

1. numpy
2. opencv-python
3. pandas
4. Pillow
5. scikit-learn
6. xgboost
7. xlrd

Step 3: Then execute "laplaceVar.py" file in python cmd.
Step 4: After step 3, execute "traindata.py" file in the same manner.
Step 5: We will test our data by executing "testdata.py" file in cmd to get the final accuracy scores of the evaluation dataset.

RESULT:

The model of 86% accuracy on the evaluation set was generated.
