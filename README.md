# Neural Network Implementation from Scratch

## Overview

This project implements a simple **feedforward neural network from scratch using Python and NumPy**.

The main purpose of this project is to understand how a neural network works internally, including forward propagation, backpropagation, loss calculation, and gradient descent.

The model is trained and evaluated on the **Iris dataset** for a 3-class classification problem.

## Objective

* Implement a neural network without TensorFlow, Keras, or PyTorch.
* Understand forward propagation and backpropagation.
* Implement the loss function and activation functions.
* Train the model using gradient descent.
* Evaluate the model using different performance metrics.
* Compare the neural network with standard machine-learning models.

## Dataset

The project uses the **Iris dataset**, which contains:

* 150 samples
* 4 input features:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
* 3 classes:

  * Setosa
  * Versicolor
  * Virginica

The dataset is divided into training and testing sets.

## Neural Network Architecture

```text
Input Layer
    4 neurons
       ↓
Hidden Layer
    8 neurons
    Sigmoid
       ↓
Output Layer
    3 neurons
    Softmax
       ↓
Class Prediction
```

### Main Components

* **Activation:** Sigmoid in hidden layer
* **Output activation:** Softmax
* **Loss:** Cross-Entropy
* **Optimizer:** Gradient Descent
* **Hidden neurons:** 8
* **Output classes:** 3

## Implementation

The neural network is implemented manually using NumPy.

The notebook includes:

1. Dataset loading and preprocessing
2. Train-test split
3. Feature scaling
4. Weight and bias initialization
5. Sigmoid activation
6. Softmax activation
7. Forward propagation
8. Cross-entropy loss
9. Backpropagation
10. Gradient descent
11. Model training
12. Performance evaluation
13. Confusion matrix
14. Model comparison

## Model Evaluation

The neural network is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Training Loss

The project also compares the neural network with:

* Logistic Regression
* Decision Tree
* Support Vector Machine (SVM)

The baseline models are evaluated using cross-validation to make the comparison more reliable.

## Results

The notebook automatically generates the final performance metrics and comparison table when executed.

The results show how a neural network implemented from scratch performs compared with standard machine-learning approaches on the Iris dataset.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

## Project Structure

```text
Neural-Network-From-Scratch/
│
├── Krishna_Kushwah_GenerativeAILabAssignment.ipynb
├── README.md
└── screenshots/
    ├── training_loss.png
    └── confusion_matrix.png
```

## How to Run

1. Clone the repository.

```bash
git clone <your-repository-link>
```

2. Open the notebook in Jupyter Notebook or Google Colab.

3. Install the required libraries if needed:

```bash
pip install numpy pandas matplotlib scikit-learn
```

4. Run all notebook cells sequentially.

## Learning Outcomes

Through this project, I learned:

* How neural-network layers work.
* How weights and biases are initialized.
* How forward propagation produces predictions.
* How backpropagation calculates gradients.
* How gradient descent updates model parameters.
* How different evaluation metrics are used.
* How neural networks compare with traditional machine-learning models.

## Conclusion

This project helped me understand the basic working of a neural network by implementing its important components manually instead of relying on deep-learning frameworks.

The comparison with traditional machine-learning models also shows that the best model depends on the complexity of the dataset and the problem being solved.

## Author

**Krishna Kushwah**
B.Tech CSE (AIML)
MIT Academy of Engineering, Alandi, Pune

---

*This project was created as part of the Generative AI Lab practice assignment.*
