# Hand Written Digit Classifier

A deep learning project that uses a **Convolutional Neural Network (CNN)** to classify handwritten digits from the MNIST dataset.

## 📌 Project Overview

This project demonstrates the complete workflow of building a handwritten digit classification model, including data preprocessing, data augmentation, CNN model development, evaluation, visualization, and error analysis.

## 🎯 Objective

To build a CNN model capable of accurately recognizing handwritten digits from **0 to 9** using the MNIST dataset.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* TensorFlow
* Keras
* Scikit-learn

## 📊 Dataset

The project uses the **MNIST handwritten digit dataset**.

* Image size: 28 × 28 pixels
* Image type: Grayscale
* Classes: 10 (digits 0–9)

## 🔄 Project Workflow

1. Load the MNIST dataset
2. Explore and preprocess the data
3. Normalize pixel values
4. Apply data augmentation
5. Build the CNN model
6. Train the model
7. Evaluate model performance
8. Visualize CNN features
9. Analyze misclassified images
10. Generate a model performance report

## 🧠 CNN Architecture

The model includes:

* Convolutional layers
* MaxPooling layers
* Flatten layer
* Dense layer
* Dropout layer
* Softmax output layer

The final layer predicts one of the **10 digit classes (0–9)**.

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Class-wise error analysis

## 🔍 Error Analysis

The project analyzes:

* Misclassified images
* Most confused digit pairs
* Class-wise error rates
* Highly confident incorrect predictions

This helps understand where and why the model makes incorrect predictions.

## 📁 Files

```text
Hand-Written-Digit-Classifier/
│
├── Capstone_Project_2.ipynb
└── README.md
```

## 🚀 How to Run

1. Clone this repository.
2. Open `Capstone_Project_2.ipynb` in Jupyter Notebook or Google Colab.
3. Install the required Python libraries.
4. Run the notebook cells sequentially.

## 👨‍💻 Author

**Rohit Gupta**

PGDM – Data Science
