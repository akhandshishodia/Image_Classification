# Image_Classifier
#Brief
In this project, I will perform image classification using four popular machine learning algorithms namely, Random Forest Classifier, KNN, Decision Tree Classifier, and Naive Bayes classifier. I'll provide the necessary explanation wherever needed. Let's start by directly jumping into implementation step-by-step.

#Agenda
In order to obtain meaningful results, a clearly outlined structure of how we will proceed is mentioned as follows.

Dataset Acquisition
Visualization
Dataset Pre-processing
Implementing a Random Forest Classifier
Implementing a KNN
Implementing a Decision Tree classifier
Implementing a Naive Bayes classifier
Results
Testing for Custom Input
Conclusion
Dataset Acquisition
The dataset used here is the CIFAR-10 dataset. It is a Keras dataset and thus can be directly downloaded from here with a simple code. It consists of ten classes, namely, airplane, automobile, bird, cat, deer, dog, frog, horse, ship and truck. Clearly, we will be working on a multi-class classification problem.

#Dataset Description
x_train: uint8 NumPy array of grayscale image data with shapes (50000, 32, 32, 3), containing the training data. Pixel values range from 0 to 255.

y_train: uint8 NumPy array of labels (integers in range 0-9) with shape (50000, 1) for the training data.

x_test: uint8 NumPy array of grayscale image data with shapes (10000, 32, 32, 3), containing the test data. Pixel values range from 0 to 255.

y_test: uint8 NumPy array of labels (integers in range 0-9) with shape (10000, 1) for the test data.

The classes for y_train and y_test are:

Label	Description
0	airplane
1	automobile
2	bird
3	cat
4	deer
5	dog
6	frog
7	horse
8	ship
9	truck
#Result
The accuracies of the four ML algorithms, we just explored for our CIFAR-10 dataset, can be summarized as follows.

Random Forest Classifier shows the best performance with 47% accuracy followed by KNN with 34% accuracy, NB with 30% accuracy, and Decision Tree with 27% accuracy. Thus, Random Forest exhibits the best performance and Decision Tree the worst. However, all the Machine learning algorithms perform poorly as indicated by the accuracies. The highest is just 47% while Deep learning algorithms outsmart them exceptionally with accuracies mostly exceeding 90%.

Although the accuracies obtained aren't high, still it helps provide a basic understanding of how different ML algorithms can be used for image classification in Python.
