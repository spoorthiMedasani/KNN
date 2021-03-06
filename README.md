## **Overview:**
K-Nearest Neighbors is a classification algorithm that assumes data points that are closer to each other have similar labels.


There are multiple approaches to calculate the distance between two points in n-dimensional space

  1. Minkowski Distance
  2. Manhattan Distance
  3. Euclidean Distance
 

Here, I used Euclidean distance to calculate the distance between nearest neighbors.
  

## **How to select K-value:**
   The k-value at which validation error is minimized is considered to be the best K-value
   

## **Drawbacks of KNN:**
  1. Curse of Dimensionality- KNN performs well with less number of features. A way around this is to use dimensionality reduction techniques like PCA (Principal Component Analysis)
  2. Requires more storage capacity when more data is available.


## **Fun Fact:**
  KNN uses all the processing capacity during Testing phase unlike most algorithms. This make training faster but testing slower and costlier.


#### ***Instead of using KNN as a black-box, I wanted to show the ins and outs of the algorithm in this code***
