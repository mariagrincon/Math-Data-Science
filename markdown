- First, I've loaded the MNIST dataset.
  
- I've generated a random matrix m of shape (10, 784) and performed matrix multiplication with the reshaped MNIST data X and applied GPU support for calculations. The result is stored in the variable y, and the predicted labels are obtained using np.argmax.

- I trained a random walk model to find the best weights `m` that can achieve the highest accuracy on the KMNIST dataset.

- I calculated accuracy by comparing the predicted labels y with the true labels Y.

-I initialize m_best and acc_best to store the best model and its accuracy.

- I performed a random walk by adding a small random perturbation m_random to m_best and then calculate the accuracy on the KMNIST training data using the new model m.
If the accuracy improves, I print and update m_best and acc_best.



