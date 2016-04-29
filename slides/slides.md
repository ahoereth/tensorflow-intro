% Theano, TensorFlow, Keras
% Andrea Suckro, Alexander Höreth
% May 2016, University of Osnabrück

# Frameworks

* Many people are comfortable with higher level languages like Python.
* High level languages commonly lack in performance by they self.
* A good framework helps you boost your performance and minimize the code necessary for repeating tasks.
* Do not reinvent the wheel.


# TensorFlow

* Efficient computation through outsourcing entire graph of interacting operations
* Good for distributed computing!
* Code is full of placeholders for the real computation

# Math

* $evidence_i = \sum_{j} W_{i,j}x_j+b_i$
* $y = softmax(evidence)$
* $softmax(x)_i = \frac{exp(x_i)}{\sum_j exp(x_j)}$

