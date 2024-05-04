Syllabus for UVicAI’s Fall 2023 Tensorflow Certification workshops
---
These are notes for the tasks covered in the Tensorflow Certification series of workshops. This performs a similar function to a syllabus.
The aim of the course is to cover those topics outlined in the TF certification handbook in manageable chunks over a semester such that participants
can gain practical experience while taking courses. Taking the certificate exam is $100, but this step is optional; the goal of this course is
to build up an understanding of ML using Tensorflow.

We will start with Google Colab because it is easy for participants to get a model up and running. Writing the certificate exam requires doing
so in PyCharm (a free IDE), so those interested in writing will need to become familiar with this program.

All slides and notebook can be found through [our Google Drive](https://drive.google.com/drive/folders/1eT2m6cfUUrefFV77irGIewQt2yugYWKM?usp=sharing)

---
<h2>Week 1: Image Classification</h2>
Goal: Get a model up and running following a simple tutorial. Become familiar with convolutional neural networks and evaluating classification results with a confusion matrix.<br>

Slides: Cifar 10 Classification<br>
Accompanying Tutorial: [Tensorflow](https://www.tensorflow.org/tutorials/keras/classification)<br>
This tutorial covers a dataset similar to CIFAR 10. Look at the notebook for Week 2 for a CIFAR10 implementation with a focus on how little needs to change.<br>
Additional Resources: [MIT - Youtube](https://www.youtube.com/watch?v=NmLK_WQBxB4)<br>
(MIT lecture that covers image processing in ML, but continues on to more complex tasks.)

---
<h2>Week 2: Image Classification</h2>
Goal: We’ll develop a framework for understanding a general ML pipeline (load data, preprocess data, define model, train model, evaluate) and use this
framework to decompose the image classification problem into manageable chunks. 
Learning objectives: confusion matrix, learning rate curves, and managing overfitting

We will be iterating on, modifying, and investigating the posted notebook.<br>

---
<h2>Week 3: Intro to time series</h2>
Timeseries data requires different preprocessing functions. This intro will focus on preparing the data to be used for forecasting,
different normalization techniques, and multiple input channels. We’ll begin to look at recurrent models, but not expecting to get completely
through that.

Additional References: [Time Series - Tensorflow](https://www.tensorflow.org/tutorials/structured_data/time_series)

---
<h2>Week 4: Recurrent Neural Networks</h2>
Building on the foundations from week 3, we will look at how recurrent networks are built and how they are designed for sequential data.
We look at local weather forecasting, and defining a model with multiple inputs. 

Additional References: [RNNs - Tensorflow](https://www.tensorflow.org/guide/keras/working_with_rnns)

---
<h2>Week 5: Work session</h2>
We’re going to review what we have covered by building a full ML pipeline for new datasets. Datasets include: Fashion MNIST for image
classification, Sunspot activity for timeseries, and maybe smartwatch-gestures (from tensorflow datasets).

---
<h2>Week 6: Word Embedding and Work Session</h2>
We’re introducing the ideas behind how we get natural language inputs into ML models. This is a short introduction to the preprocessing
steps commonly used. Instead of jumping into a notebook to see how this is performed, we will continue our work session from last time
with a focus on the timeseries dataset (sunspots).

Additional Reference: [Text Classification - Keras](https://keras.io/examples/nlp/text_classification_from_scratch/)

---
<h2>Week 7: Next Word Prediction</h2>
We are recapping text processing and applying it to a simple task: movie review classification. The movie reviews are short user written
reviews for some movie, with the task being to classify whether the reviewer gives it a thumbs up or thumbs down. This approaches the review
as a disordered “bag of words”, relying on the words, but not considering the word order.

