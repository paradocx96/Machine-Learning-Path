# Day 2

## Recap: Day 1

### SUPERVISED LEARNING ALGORITHMS

* k-Nearest Neighbors
* Linear Regression
* Logistic Regression
* Support Vector Machines (SVMs)
* Decision Trees and Random Forests
* Neural networks^2

### UN-SUPERVISED LEARNING ALGORITHMS

1. Clustering
   - K-Means
   - DBSCAN
   - Hierarchical Cluster Analysis (HCA)

2. Anomaly detection and novelty detection
   - One-class SVM
   - Isolation Forest

3. Visualization and dimensionality reduction
   - Principal Component Analysis (PCA)
   - Kernel PCA
   - Locally-Linear Embedding (LLE)
   - t-distributed Stochastic Neighbor Embedding (t-SNE)

4. Association rule learning
   - Apriori
   - Eclat

## INSTANCE BASED LEARNING vs MODEL BASED LEARNING

### Instance Based Learning

System learns examples by heart and generalizes the new cases by comparing it with the similarities.

<img src="assets/InstanceBasedLearning.png" alt="InstanceBasedLearning" width="50%" />  

### Model Based Learning

Building a model to predict the generalization.

<img src="assets/ModelBasedLearning.png" alt="ModelBasedLearning" width="50%" />  

### EX: DOES MONEY MAKES PEOPLE HAPPIER?

**GDP per capita vs Life satisfaction data set**  

<img src="assets/Ex1_0.png" alt="Ex1_0" width="30%" />  

**Can you see a Model?**

<img src="assets/Ex1_1.png" alt="Ex1_1" width="30%" />  
<br/>
<img src="assets/Ex1_2.png" alt="Ex1_2" width="30%" />  

**Determine the best model using the parameters** 

<img src="assets/Ex1_3.png" alt="Ex1_3" width="30%" />  

* Specify a performance measure(Utility function or cost function)
* Utility(fitness) function determines how good your model is
* Cost function determines how bad the model is
* For linear regression problems normally use the cost function which measures the distance between linear model predictions and the training examples.  

**Best fit Model**

<img src="assets/Ex1_4.png" alt="Ex1_4" width="30%" />  

