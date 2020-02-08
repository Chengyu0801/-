In the course of four days' study, what impresses me most is the issue of housing price forecast in Boston. Peter asked for two different ways to realize the house price forecast. The first method is to find the best "maximum depth" parameter through continuous training and decision tree algorithm. After searching the codes on the Internet, the fitting degree of this method can reach 0.923. However, there are still some problems running on jupyter. For example, some function names in Python 3 have changed and need to be the latest. In the process of visual execution, the program constantly reports errors, looks for solutions on the Internet, and tries various methods, but fails. At last, a large number of materials are consulted to find a solution to the problem.
Secondly, Peter introduced many machine learning algorithms at the beginning of the course, including KNN, decision tree, ANN, SVR, etc. I choose KNN algorithm to try to solve the Boston house price prediction problem. After obtaining the information, first import the required database, then normalize the data, and use KNN model to predict the price. It is found that with the gradual increase of N ~ U neighborhood, its model prediction ability gradually increases, but when N ~ U neighborhood is greater than 2, the model score tends to decline. Suppose n ﹐ neighbors = 2. According to the test results, the score of KNN model is 0.693957. At the same time, I tried SVR, but the result was obviously incorrect. I also need to learn and improve.
