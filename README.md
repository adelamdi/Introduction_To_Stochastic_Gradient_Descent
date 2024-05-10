# Introduction to stochastic gradient descent
Stochastic Gradient Descent (SGD) is a variant of the gradient descent algorithm that is used for optimizing machine learning models. SGD utilizes a randomly chosen subset of the training data, referred to as a mini-batch, to compute the gradient of the cost function in each iteration.

Importing randomness into the optimization process, leading to a noisier convergence path compared to methods using the entire dataset but the path itself is not the primary concern. As long as SGD converges to a sufficiently good minimum . The benefits of faster training times can outweigh the noisier path.

The main advantage of SGD is its computational efficiency, especially when dealing with large datasets. The computational cost per iteration is significantly reduced compared to traditional gradient descent methods that require processing the entire dataset.

Stochastic gradient descent algorithm has 3 key steps:
1. Initialization and setting parameters
3. Stochastic Gradient Descent Loop (Shuffling - Iterating - Computing the gradient - Updating parameters - Evaluating convergence)
4. Return Optimized Parameters

**We will delve into a more detailed basic concepts, explanation of steps, stochastic gradient descent python code and a simple example in [this jupyter notebook](Stochastic_gradient_descent.ipynb).**
