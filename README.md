# Mohd-Mohsin-Khan-ML

## Supervised Learning

Supervised learning, also known as supervised machine learning, is a subcategory of machine learning and artificial intelligence. It is defined by its use of labeled datasets to train algorithms that to classify data or predict outcomes accurately.  is the machine learning task of learning a function that maps an input to an output based on example input-output pairs. It infers a function from labeled training data consisting of a set of training examples. 

![Supervised Learning](https://user-images.githubusercontent.com/78999231/184416861-46ac4fe7-6abc-42f5-aa06-0d1e8625a0da.jpg)


## Unsupervised Learning

Unsupervised learning, also known as unsupervised machine learning, uses machine learning algorithms to analyze and cluster unlabeled datasets. These algorithms discover hidden patterns or data groupings without the need for human intervention. It is a type of algorithm that learns patterns from untagged data. The hope is that through mimicry, which is an important mode of learning in people, the machine is forced to build a compact internal representation of its world and then generate imaginative content from it.

![Unsupervised Learning](https://user-images.githubusercontent.com/78999231/184417466-87b5d68b-13c0-41d6-afe1-62a683ccce73.png)

## Underfitting and Overfitting

Underfitting is a scenario in data science where a data model is unable to capture the relationship between the input and output variables accurately, generating a high error rate on both the training set and unseen data.

Overfitting is a concept in data science, which occurs when a statistical model fits exactly against its training data. When this happens, the algorithm unfortunately cannot perform accurately against unseen data, defeating its purpose.

![Underfitting vs Overfitting](https://user-images.githubusercontent.com/78999231/184418202-15d69c6f-bd5d-488d-8015-6897b4c46975.png)

## Classification Problem Evaluation Metrics

Evaluation metrics are tied to machine learning tasks. There are different metrics for the tasks of classification and regression. Some metrics, like precision-recall, are useful for multiple tasks. Classification and regression are examples of supervised learning, which constitutes a majority of machine learning applications. Using different metrics for performance evaluation, we should be able to improve our model’s overall predictive power before we roll it out for production on unseen data. Without doing a proper evaluation of the Machine Learning model by using different evaluation metrics, and only depending on accuracy, can lead to a problem when the respective model is deployed on unseen data and may end in poor predictions.

### Classification Metrics

Classification is about predicting the class labels given input data. In binary classification, there are only two possible output classes(i.e., Dichotomy). In multiclass classification, more than two possible classes can be present. It’ll focus only on binary classification.

![1_xgiEyLEym8eh-HeO98WR6w](https://user-images.githubusercontent.com/78999231/184419117-af4849bf-81ae-43b1-bc69-1f1ecd62def8.png)

### Accuracy

Accuracy simply measures how often the classifier correctly predicts. We can define accuracy as the ratio of the number of correct predictions and the total number of predictions.

![1_R6jP_uvlkcxtQSa264N3Sw](https://user-images.githubusercontent.com/78999231/184419242-c51ae66d-80af-447b-8645-fab43331369b.png)
![1_zzR88UEu6A786mPYcRVDhQ](https://user-images.githubusercontent.com/78999231/184419282-4e63131c-499f-4148-a2fc-104051a2f0f3.png)

### Confusion Matrix

Confusion Matrix is a performance measurement for the machine learning classification problems where the output can be two or more classes. It is a table with combinations of predicted and actual values.

A confusion matrix is defined as thetable that is often used to describe the performance of a classification model on a set of the test data for which the true values are known.

![0_UnezxOaQyU6Fb6D3](https://user-images.githubusercontent.com/78999231/184419446-1c117717-942e-436b-b371-9a433d8e96bf.jpg)

- True Positive: We predicted positive and it’s true. In the image, we predicted that a woman is pregnant and she actually is.

- True Negative: We predicted negative and it’s true. In the image, we predicted that a man is not pregnant and he actually is not.

- False Positive (Type 1 Error)- We predicted positive and it’s false. In the image, we predicted that a man is pregnant but he actually is not.

- False Negative (Type 2 Error)- We predicted negative and it’s false. In the image, we predicted that a woman is not pregnant but she actually is.

### Conclusion

Understanding how well a machine learning model will perform on unseen data is the main purpose behind working with these evaluation metrics. Metrics like accuracy, precision, recall are good ways to evaluate classification models for balanced datasets, but if the data is imbalanced then other methods like ROC/AUC perform better in evaluating the model performance.

ROC curve isn’t just a single number but it’s a whole curve that provides nuanced details about the behavior of the classifier. It is also hard to quickly compare many ROC curves to each other.

- [Mohd Mohsin Khan](https://github.com/mohdmohsin123)
- 6388515249
- [LinkedIn](https://www.linkedin.com/in/mohd-mohsin-khan-1a3167202/)
