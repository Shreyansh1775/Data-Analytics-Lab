# Data-Analytics-Lab

Question 1

The current implementation uses a fixed number of epochs (epochs=1000) as the convergence criterion. The gradient descent algorithm iterates for the specified number of epochs, regardless of whether the model has converged.

To improve the convergence criterion, we can implement an early stopping mechanism based on the change in the loss function (Mean Squared Error). For example, we could stop the training if the change in MSE between consecutive iterations falls below a small threshold.

Question 2

Advantage of Averaging the Cost

1. Reduced Variance**: Smoother gradients, less noise from individual data points.
2. Better Generalization**: Less overfitting to noise, improves performance on unseen data.
3. Stable Convergence**: Smoother cost curve, avoids erratic updates.
4. Scalability**: More efficient for larger datasets, reduces influence of single data points.
5. Consistent Learning Rate**: Helps maintain a steady and stable learning rate.
