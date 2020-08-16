K-Nearest Neighbors is a classification assumes that data points that are close to each other have similar labels.

There are multiple approaches to calculate the distance between two points in n-dimentional space. 
  1. Minkowski Distance
  2. Manhattan Distance
  3. Euclidean Distance
 
  Here, I used Euclidean distance to calculate the deistance between nearest neighbors.
  
How to select K-value:
   The k-value at which validation error is minimized is considered to be the best K-value
   
Drawbacks of KNN:
  1. Curse of Dimensionality- KNN performs well with less features. A way around this is to use dimensionality reduction techniques like PCA(Principal Component Analysis)
  2. Requires more storage capacity when more data is available.
  
Fun Fact:
  KNN uses all the processing capacity during Testing phase unlike most of the algorithms. This make training faster but testing slower and costlier.
