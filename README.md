----

### Machine Learning

This course provides an introduction to machine learning. Machine learning explores the study and construction of algorithms that can learn from and make predictions on data. Such algorithms operate by building a model from example inputs in order to make data-driven predictions or decisions, rather than following strictly static program instructions.

Topic categories include supervised, unsupervised, and reinforcement learning. Students will learn how to apply machine learning methods to solve problems in computer vision, natural language processing, classification, and prediction. Fundamental and current state-of-the-art methods including boosting and deep learning will be covered. Students will reinforce their learning of machine learning algorithms with hands-on tutorial oriented laboratory exercises using Jupyter Notebooks.

Prerequisites: MA-262 Probability and Statistics; programming maturity, and the ability to program in Python.  

Helpful: CS3851 Algorithms, MA-383 Linear Algebra, Data Science.  

ABET: Math/Science, Engineering Topics.

2-2-3 (class hours/week, laboratory hours/week, credits)

Lectures are augmented with hands-on tutorials using Jupyter Notebooks. Laboratory assignments will be completed using Python and related data science packages: NumPy, Pandas, ScipPy, StatsModels, Scikit-learn, Matplotlib, TensorFlow, Keras, PyTorch.

Outcomes:   
- Understand the basic process of machine learning.    
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts and architectures including representation learning Multi-layer Perceptrons, Convolutional Neural Networks, Recurrent Neural Networks, and Attention Mechanisms.    
- The ability to assess the quality of predictions and inferences.  
- The ability to apply methods to real world data sets.  

References:  

*[Hands-On Machine Learning with Scikit-Learn and TensorFlow
Concepts, Tools, and Techniques to Build Intelligent Systems (MLSLT), Aurélien Géron. O'Reilly Media, 2017](http://shop.oreilly.com/product/0636920052289.do)

[Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition, by Aurélien Géron, Publisher: O'Reilly Media, Inc. Release Date: June 2019
ISBN: 9781492032649](https://www.safaribooksonline.com/library/view/hands-on-machine-learning/9781492032632/)

*[Deep Learning with Python (DLP), François Chollet. Manning, 2017.](https://www.manning.com/books/deep-learning-with-python)

[Deep Learning, Ian Goodfellow, Yoshua Bengio, and Aaron Courville. MIT Press, 2016.](https://www.deeplearningbook.org/)

[An Introduction to Statistical Learning: with Applications in R Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani. 2015 Edition, Springer.](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf)

[Python Data Science Handbook, Jake VanderPlas, O'Reilly.](https://jakevdp.github.io/PythonDataScienceHandbook/)

Mining of Massive Datasets. Anand Rajaraman and Jeffrey David Ullman. http://www.mmds.org/

---

### Week 1: Intro to Machine Learning, Linear Regression

#### Lecture:    
1. [Syllabus](syllabus.pdf)

1. [Introduction to Machine Learning](slides/IntroMachineLearning.pdf)   
- Demonstrations   
- Reading: MLSLT Ch. 1  

2. [Linear Regression](slides/LinearRegressionML_Jay.pdf)  

3. [Introduction to Git and GitHub](slides/00_git_github.pdf)
-  Reference: [git - the simple guide](http://rogerdudler.github.io/git-guide/)   

4. [Machine Learning Foundations](slides/MachineLearningFoundations.pdf)  
- [End to end machine learning](notebooks/02_end_to_end_machine_learning_project.ipynb)  
- [Image Classification Using Deep Learning](https://github.com/jayurbain/deep-learning-foundations/blob/master/image-classification/dlnd_image_classification.ipynb)  
- [Back Pain](https://github.com/jayurbain/BackPain/blob/master/Back%20Pain%20Data%20Analysis.ipynb)     
- [Vehicle Detection](https://github.com/jayurbain/CarND-Vehicle-Detection)    

- Reading: MLSLT Ch. 2   

#### Lab Notebooks:
- [Using Jupyter Notebooks](notebooks/lab_0_python/lab_0_jupyter.ipynb)  
- [Python Programming for Data Science](notebooks/lab_0_python/lab_0_python.ipynb) *Submission required*
- [Python Numpy](notebooks/4&#32;-&#32;Python&#32;Numpy.ipynb) *Submission required*    

*Note: Initiate walkthrough of hands-on notebooks with students, let them complete submissions on their own.*  

#### Optional tutorial notebooks:   
- [Python Objects, Map, Lambda, and List Comprehensions](<notebooks/3&#32;-&#32;Python&#32;Objects&#32;Map&#32;Lambda&#32;List&#32;Comprehensions.ipynb>) 
- [Dates and Time](notebooks/2&#32;-&#32;Dates&#32;and&#32;TIme.ipynb)  
- [Python Numpy Aggregates](notebooks/5&#32;-&#32;Python&#32;Numpy&#32;Aggregates.ipynb)
- [Pandas Data Manipulation](notebooks/6&#32;-&#32;Pandas&#32;Data&#32;Manipulation.ipynb)   
- [Python Reading and Writing CSV files](notebooks/7&#32;-&#32;Python&#32;Reading&#32;and&#32;Writing&#32;CSV&#32;files.ipynb)  
- [Data Visualization](notebooks/8&#32;-&#32;Data&#32;Visualization.ipynb)  
- [Python Programming Style](notebooks/lab_0_python/python_programming_style.ipynb) 

Outcomes addressed in week 1:   
- Understand the basic process of machine learning:    
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  

---

### Week 2: Gradient Descent Learning, Logistic Regression

#### Lecture:   

1. [Gradient Descent](slides/LogisticRegressionML_Jay.pdf)   
- [Normal Equation Derivation](http://jayurbain.com/msoe/cs498-machinelearning/Normal%20Equation%20derivation%20for%20linear%20regression.pdf)   

2. [Logistic Regression](slides/LogisticRegressionML_Jay.pdf)    

#### Lab Notebooks:
- [Gradient Descent Learning](notebooks/gradient_descent_assignment.ipynb) *Submission required*

#### Optional exercise:   
[Online Machine Learning with Stochastic Gradient Descent](notebooks/Online%20Machine%20Learning.ipynb)

Outcomes addressed in week 2:   
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.   

---

### Week 3: Model Selection and Regularization, Decision Trees  

#### Lecture:   

1. [Model selection and regularization](slides/Regularization_and_overfittingML.pdf)  

2. [Decision Trees, Overfitting, Model Selection, Techniques to Improve Classifier Accuracy Slides](slides/dm08ClassBasic.pdf)  
- [Information Gain Calculation Spreadsheet](http://jayurbain.com/msoe/cs4881/infogain.xls)

#### Lab Notebooks:
[Introduction to Machine Learning with SciKit Learn.ipynb](notebooks/Introduction%20to%20Machine%20Learning%20with%20SciKit%20Learn.ipynb)   
[Supervised Learning - Linear Regression](notebooks/Supervised%20Learning%20-%20%20Linear%20Regression.ipynb)   *Submission required*   
[Supervised Learning - Logistic Regression](notebooks/Supervised%20Learning%20-%20Logistic%20Regression.ipynb)  *Submission required*   
[Generalized Linear Models](notebooks/Generalized%20Linear%20Models%20and%20Regularization.ipynb) *Optional*   

Outcomes addressed in week 3:    
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  

---

#### Week 4: Probabilistic Models

#### Lecture:

1. [Validation, Bagging, Boosting, Random Forests](slides/validation_boostrap_boosting.pdf)

2. [Naive Bayes Slides 87-102](slides/dm08ClassBasic.pdf)

3. [Bayesian Networks](slides/m14-bayesian.pdf)  *optional*   
- [BayesianNetworkSprinklerExample.xls](slides/BayesianNetworkSprinklerExample.xls)

#### Lab Notebooks:  

- [Decision Trees with Scikit Learn](notebooks/Decision%20Trees.ipynb) *Submission required*   
- [Random Forests and Boosting](notebooks/Lab9_DT_RF_Boosting/RF_and_Boosting.ipynb)  
- XGBoost  

Outcomes addressed in week 4:   
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  

---

### Week 5: Unsupervised Learning

#### Lecture:

1. [K-Means Clustering](slides/dm10ClusBasic.pdf)  
2. [Hierarchical Agglomerative and Probabilistic Clustering](slides/dm10ClusBasic.pdf)  

#### Lab Notebooks:   
- [Clustering](notebooks/Clustering.ipynb)  *Submission required*      

Outcomes addressed in week 5:   
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  

---

#### Week 6: Midterm, Dimensionality Reduction

#### Lecture:
1. [Dimensionality Reduction](slides/DimensionalityReduction.pdf)  

2. [Midterm exam](http://jayurbain.com/msoe/cs498-machinelearning/Machine%20Learning%20Midterm%20Exam%20Review.pdf)   

#### Lab Notebooks:   
- [SVD](notebooks/Lab6_Classification_PCA/Singular&#32;Value&#32;Decomposition.ipynb)  *Hands-on only*   
- [PCA](notebooks/Lab6_Classification_PCA/classification-and-pca-lab.ipynb)   *Hands-on only*  

Outcomes addressed in week 6:
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  

---

#### Week 7: Introduction to Neural Networks and Deep Learning  

#### Lecture:

1. [Deep Learning Introduction 1](slides/Deep&#32;Learning&#32;Introduction.pdf)

2. [Deep Learning Introduction 2](slides/dli/Lecture-2-1-dl-intro-urbain.pdf)

3. [Backpropagation](slides/dli/Lecture-2-3-dl-backprop2-urbain.pdf)   

#### Lab Notebooks:  
*Option 1*   
- [Introduction to TensorFlow](notebooks/deep_learning_intro/Tensorflow-task.ipynb) *Submission required*   
- [Neural Network Fundamentals](notebooks/deep_learning_intro/my1stNN.ipynb) *Submission required*   
*Option 2*   
- [Introduction to TensorFlow](https://github.com/jayurbain/TensorFlowIntro) *Submission required*   
- [Neural Network Fundamentals](notebooks/NeuralNetworkIntro-Student.ipynb) *Submission required*   

*Note: need to prune answers from notebooks*   

Outcomes addressed in week 8:
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.   
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts and architectures including representation learning Multi-layer Perceptrons, Convolutional Neural Networks, Recurrent Neural Networks, and Attention Mechanisms.    

#### Week 8: Deep Learning for Computer Vision

#### Lecture:

1. [Deep Learning for Computer Vision](slides/dli/Lecture-3-1-convnets-history-urbain.pdf)  

2. [Convnets](slides/dli/Lecture-3-2-convnets-intro-urbain.pdf)  

#### Lab Notebooks:   
[Keras Intro](notebooks/deep_learning_intro/Keras-task.ipynb) *Submission required*   
[Image Classification](notebooks/computer_vision/cnn_cifar10.ipynb) *Submission required*   

*Note: need to prune answers from notebooks*   

Outcomes addressed in week 9:
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.   
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts and architectures including representation learning Multi-layer Perceptrons, Convolutional Neural Networks, Recurrent Neural Networks, and Attention Mechanisms.    

---

#### Week 9: Deep Learning for NLP

#### Lecture:

1. [NLP Classification](slides/nlp/2&#32;NLP%20Text&#32;Classification.pdf)  

2. *Optional* [Convnets for Structured Prediction](slides/dli/Lecture-3-3-convnets-struc-pred-nlp-urbain.pdf)  

3. [NLP Translation](slides/nlp/3&#32;NLP&#32;Text&#32;Translations.pdf)  

#### Lab Notebooks:     
- [NLP Classification](notebooks/nlp/Text&#32;Classification/SentimentClassification.ipynb)   
- [NLP Translation ](notebooks/nlp/Text&#32;Translation/TextTranslation.ipynb)   

*Note: need to prune answers from notebooks*   

Outcomes addressed in week 9:   
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.   
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts and architectures including representation learning Multi-layer Perceptrons, Convolutional Neural Networks, Recurrent Neural Networks, and Attention Mechanisms.    


---

#### Week 10:  Generative Deep Learning

#### Lecture:
1. [Future Challenges](slides/dli/Lecture-7-1-future-challenges-urbain.pdf)

2. [Auto-encoder, Variational Auto-encoder, GANs]()  *TBD: probably too advanced*    

#### Lab Notebooks:  
Complete assignments   

Outcomes addressed in week 10:
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.   
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts including representation learning.    
---
