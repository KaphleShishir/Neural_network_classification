# Neural Network Classification

This project explores neural network classification using PyTorch. It covers both binary classification and multi-class classification on simple synthetic datasets.

## What I Learned

1. **Binary Classification:** Determining if a point is inside a circle using `make_circles` from scikit-learn.
2. **Multi-class Classification:** Classifying points into multiple clusters using `make_blobs` from scikit-learn.
3. **Activation Functions:** How ReLU and Sigmoid help the model capture non-linear patterns.
4. **Logits, Probabilities, and Labels:** Converting raw model outputs to predictions using sigmoid for binary and softmax for multi-class classification.
5. **Loss Functions:** Using `BCEWithLogitsLoss` for binary and `CrossEntropyLoss` for multi-class classification.
6. **Optimizers:** Using Adam and SGD to improve training efficiency.
7. **Visualization:** Understanding decision boundaries and the difference between linear and non-linear patterns.

## Key Takeaways

- Non-linearity is crucial; stacking linear layers alone cannot model complex patterns.
- Proper choice of activation functions, learning rates, and loss functions can significantly improve model performance.
- Visualizing the model’s behavior helps understand how it learns.

## Tools and Libraries

- Python
- PyTorch
- scikit-learn
- Matplotlib
- Pandas

This project is a great starting point for understanding the fundamentals of neural networks and classification problems before diving into more advanced topics like CNNs and computer vision.
