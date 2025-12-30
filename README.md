<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Neural Network Classification</title>
</head>
<body>
    <h1>Neural Network Classification</h1>

    <p>This project explores neural network classification using PyTorch. It covers both binary classification and multi-class classification on simple synthetic datasets.</p>

    <h2>What I Learned</h2>
    <ol>
        <li><strong>Binary Classification:</strong> Determining if a point is inside a circle using <code>make_circles</code> from scikit-learn.</li>
        <li><strong>Multi-class Classification:</strong> Classifying points into multiple clusters using <code>make_blobs</code> from scikit-learn.</li>
        <li><strong>Activation Functions:</strong> How ReLU and Sigmoid help the model capture non-linear patterns.</li>
        <li><strong>Logits, Probabilities, and Labels:</strong> Converting raw model outputs to predictions using sigmoid for binary and softmax for multi-class classification.</li>
        <li><strong>Loss Functions:</strong> Using <code>BCEWithLogitsLoss</code> for binary and <code>CrossEntropyLoss</code> for multi-class classification.</li>
        <li><strong>Optimizers:</strong> Using Adam and SGD to improve training efficiency.</li>
        <li><strong>Visualization:</strong> Understanding decision boundaries and the difference between linear and non-linear patterns.</li>
    </ol>

    <h2>Key Takeaways</h2>
    <ul>
        <li>Non-linearity is crucial; stacking linear layers alone cannot model complex patterns.</li>
        <li>Proper choice of activation functions, learning rates, and loss functions can significantly improve model performance.</li>
        <li>Visualizing the model’s behavior helps understand how it learns.</li>
    </ul>

    <h2>Tools and Libraries</h2>
    <ul>
        <li>Python</li>
        <li>PyTorch</li>
        <li>scikit-learn</li>
        <li>Matplotlib</li>
        <li>Pandas</li>
    </ul>

    <p>This project is a great starting point for understanding the fundamentals of neural networks and classification problems before diving into more advanced topics like CNNs and computer vision.</p>
</body>
</html>
