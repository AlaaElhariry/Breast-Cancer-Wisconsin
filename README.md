# Breast-Cancer-Wisconsin
# intro
This breast cancer databases was obtained from the University of Wisconsin Hospitals, Madison from Dr. William H. Wolberg. If you publish results when using this database, then please include this information in your acknowledgements.
# data cleaning stage 
Below we will correct some of the inconsistencies in the data:

data has duplicated values(9)
name of columns must be changed to understand
column(Bare Nuclei )should be change to int
also, column (Bare Nuclei)has wrong value is ? should change
# model 
we used K-Nearst Neighbours algorithm.K-Nearest Neighbors is a supervised learning algorithm. Where the data is 'trained' with data points corresponding to their classification. To predict the class of a given data point, it takes into account the classes of the 'K' nearest data points and chooses the class in which the majority of the 'K' nearest data points belong to as the predicted class.The best accuracy was with 0.9857142857142858 with k= 1.
