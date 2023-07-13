# Sampling-techniques
The sampling techniques used are random sampling, stratified sampling, and systematic sampling. The models used were SVM, Random Forest Classifier, Logistic Regression, KNN Classifier, Decision Tree Classifier, and Naive Bayes Classifier. Out of these models, the Random Forest Classifier gave the highest accuracy when using random sampling




Random Sampling: Random sampling is a technique where each individual or data point in a population has an equal chance of being selected for the sample. It involves randomly selecting observations from the entire population without any specific criteria. This technique is often used when the population is homogeneous, and each individual is independent of others. Random sampling helps in reducing bias and ensures the representativeness of the sample.

Stratified Sampling: Stratified sampling involves dividing the population into homogeneous subgroups or strata based on certain characteristics or attributes. The subgroups are formed in such a way that they are internally similar but differ from each other. Then, a random sample is selected from each subgroup in proportion to its representation in the population. This technique ensures that important subgroups are adequately represented in the sample and helps in capturing the variability present in the population.

Systematic Sampling: Systematic sampling involves selecting individuals from a population at regular intervals. It follows a systematic pattern, where the first individual is randomly selected from the first k individuals, and then every kth individual is selected thereafter. The value of k is determined based on the desired sample size and the total population size. Systematic sampling is a simpler alternative to random sampling and provides a representative sample when there is no specific pattern or structure in the population.

Machine Learning Models:

Support Vector Machine (SVM): SVM is a supervised machine learning algorithm that is used for classification and regression tasks. It works by finding an optimal hyperplane that separates the data into different classes. SVM aims to maximize the margin between the decision boundary and the closest data points. It can handle both linear and non-linear data by using kernel functions. SVM is known for its effectiveness in handling high-dimensional data and has good generalization properties.

Random Forest Classifier: Random Forest is an ensemble learning method that combines multiple decision trees to create a more accurate and robust classifier. Each tree is trained on a random subset of the features and the samples. During the prediction, each tree in the forest independently predicts the class, and the final prediction is determined by majority voting. Random Forests are known for their ability to handle high-dimensional data, avoid overfitting, and provide feature importance rankings.

Logistic Regression: Logistic Regression is a statistical model used for binary classification problems. It models the relationship between the input variables and the probability of a binary outcome. Logistic Regression uses the logistic function (sigmoid function) to transform the output into a probability score. It estimates the parameters of the model by maximizing the likelihood function. Logistic Regression is widely used due to its simplicity, interpretability, and ability to handle linear relationships.

K-Nearest Neighbors (KNN) Classifier: KNN is a non-parametric classification algorithm that works by finding the k nearest neighbors to a given data point and assigns the class based on majority voting. The value of k determines the number of neighbors considered for classification. KNN does not make any assumptions about the underlying data distribution and can handle non-linear decision boundaries. It is simple to understand and implement but can be computationally expensive for large datasets.

Decision Tree Classifier: Decision Tree is a tree-based supervised learning algorithm that partitions the data into smaller subsets based on the values of input features. It constructs a tree-like model where each internal node represents a test on a feature, each branch represents an outcome of the test, and each leaf node represents a class label. Decision Trees are interpretable, handle both categorical and numerical data, and can capture complex decision boundaries. However, they are prone to overfitting and may not generalize well to unseen data.

Naive Bayes Classifier: Naive Bayes is a probabilistic classifier based on Bayes' theorem with an assumption of independence between the features. It calculates the probability of each class given the input features and selects the class with the highest probability. Naive Bayes is computationally efficient, even with a large number of features. It works well with categorical and discrete data and performs well in text classification and spam filtering tasks. However, the independence assumption may not hold in some cases, impacting the accuracy of the model.

In the given project, random sampling, stratified sampling, and systematic sampling were used to create representative samples from the population. Among the models evaluated, the Random Forest Classifier achieved the highest accuracy when random sampling was used. The Random Forest algorithm combines the predictions of multiple decision trees, providing a robust and accurate classification model. However, the choice of sampling technique and model may vary depending on the specific characteristics of the dataset, problem domain, and desired objectives.





Regenerate response
