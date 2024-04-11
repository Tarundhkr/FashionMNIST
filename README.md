# FashionMNIST
In this project, we explore the effectiveness of Convolutional Neural Networks (CNNs) compared to a baseline linear model for the classification of the FashionMNIST dataset. FashionMNIST is a popular benchmark dataset containing 70,000 grayscale images of fashion items categorized into 10 classes.

The primary objective of this project is to investigate and contrast the performance of a CNN architecture against a simpler linear model in classifying FashionMNIST images. By comparing the results, we aim to understand the strengths and weaknesses of each approach in handling this image classification task.

Methodology:

Data Preparation: We begin by preprocessing the FashionMNIST dataset, including normalization and splitting it into training and testing sets.

Baseline Linear Model: We construct a baseline linear model consisting of simple linear layers without any convolutional or pooling operations. This model serves as our reference point for evaluating the performance of the CNN architecture.

Convolutional Neural Network (CNN): Next, we design and train a CNN architecture tailored for image classification tasks. The CNN comprises convolutional layers, activation functions, pooling layers, and fully connected layers, followed by softmax activation for multi-class classification.

Model Training and Evaluation: Both the baseline linear model and the CNN are trained on the FashionMNIST training set and evaluated on the testing set. We measure key performance metrics such as accuracy, precision, recall, and F1-score to assess the classification performance of each model.

Comparison and Analysis: The results obtained from the baseline linear model and the CNN are compared and analyzed to discern differences in classification accuracy and generalization capabilities. We also visualize model predictions and misclassifications to gain insights into their respective strengths and limitations.

Conclusion:

In conclusion, this project sheds light on the effectiveness of CNNs compared to baseline linear models for the task of image classification. By contrasting their performance, we gain valuable insights into the suitability of each approach for image classification tasks, thereby informing future model selection and development efforts in similar domains.
