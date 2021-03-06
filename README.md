Support Vector Machines
=====
This is the week 6 assignment of [Coursera Machine Learning](https://www.coursera.org/course/ml) class.

Part I
-------
First part of this program experiments with SVM, a large margin classifier algorithm, using three datasets. All of the three data sets consists of two classes. The goal is to find the decision boundary of classification. For dataset1 the effect of C parameter on the decision boundary is explored with a SVM using linear kernel. Dataset2 requires using a svm with Gaussian kernel to find the nonlinear decision boundary. Dataset3 also has a nonlinear decision boundary and the task is to find the optimal C sigma pair by training using an additional cross-validation set.

Completed methods are as follows:

### gaussianKernel.m 
This method returns the similarity between two input entry vectors using Gaussian kernel with bandwidth sigma

### dataset3Params.m 
This method returns optimal C and sigma parameters to use for Dataset 3. The optimal learning parameter pair is found by iterating through all possible combinations of candidate values of C and sigma and minimizing the prediction error, which is given by svmPrediction function.

Other starter code and datasets provided by the course are shown below:

> ex6.m - Octave script for the first half of the exercise <br\ >
> ex6data1.mat - Example Dataset 1 <br\ >
> ex6data2.mat - Example Dataset 2 <br\ >
> ex6data3.mat - Example Dataset 3 <br\ >
> svmTrain.m - SVM training function <br\ >
> svmPredict.m - SVM prediction function <br\ >
> plotData.m - Plot 2D data <br\ >
> visualizeBoundaryLinear.m - Plot linear boundary <br\ >
> visualizeBoundary.m - Plot non-linear boundary <br\ >
> linearKernel.m - Linear kernel for SVM <br\ >


Part II
-------
The second part of the program is to build a spam filter using svm. 

Completed methods are as follows:

##### processEmail.m 
Email preprocessing

##### emailFeatures.m
Feature extraction from emails


Other starter code and datasets provided by the course are shown below:

> ex6_spam.m - Octave script for the second half of the exercise <br\ >
> spamTrain.mat - Spam training set<br\ >
> spamTest.mat - Spam test set<br\ >
> emailSample1.txt - Sample email 1<br\ >
> emailSample2.txt - Sample email 2<br\ >
> spamSample1.txt - Sample spam 1<br\ >
> spamSample2.txt - Sample spam 2<br\ >
> vocab.txt - Vocabulary list<br\ >
> getVocabList.m - Load vocabulary list<br\ >
> porterStemmer.m - Stemming function<br\ >
> readFile.m - Reads a file into a character string<br\ >

