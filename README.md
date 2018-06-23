# Course-Learning_Algorithms
Projects and notes of CSE250b - Learning Algorithms
1. Handwritten digit recognition using a Gaussian generative model
  - MNIST data from http://yann.lecun.com/exdb/mnist/index.html
  - model each class as a multivariate (784-dimensional) Gaussian
  - smooth the covariance matrices
  
2. Discovering relevant features in regression
  - identify ten features with noise from original 100 features
  - Recursive Feature Elimination(RFE)
  - linear regression using the Lasso

3. Prototype selection for nearest neighbor
  - K-Means algorithm (ClusterCentroids API)
  - compare  with uniform-random selection & Condensed Nearest Neighbour (CNN)
  - improvement reflected by performance and storage requirements
  
4. Coordinate descent
  - wine dataset at https://archive.ics.uci.edu/ml/datasets/Wine
  - implement Random-feature CDN, Cyclic CDN, GS CDN with Newton method by finding continuous second-order derivatives
  - many other adaptive and mature methods such as coordinate-gradient descent, pathwise coordinate descent with shrink operator

5. Multi-class Classification & Kernel Methods
  - implement multi-class perceptron, kernel(quadratic & RBF) perceptron, multi-class kernel(linear & quadratic) SVM 
  - plot decision regions and all data points with different colors and shapes for different labels
  
6. Word Embeddings
  - cluster words (Brown corpus) with similar meanings by pointwise mutual information
  - reduce the dimensionality of word embeddings
  - investigate the resulting embedding in two ways: nn & clustering (Gaussian Mixture & K-Means)

7. PCA and Manifolds
  - PCA: animals data set: http://attributes.kyb.tuebingen.mpg.de; visualize these animals in 2-d
  - MDS: reconstruct the locations of ten US cities given only the distances between them
