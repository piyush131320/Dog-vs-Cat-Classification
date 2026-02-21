# Dog-vs-Cat-Classification
Dog vs Cat Image Classification using Transfer Learning (Deep Learning project). This project uses a pre-trained CNN model to classify images of dogs and cats with high accuracy.

🐶🐱 Dog vs Cat Classification using Transfer Learning
📌 Project Overview

This project implements a Deep Learning-based Image Classification model to classify images as Dog or Cat using Transfer Learning.

Instead of training a CNN from scratch, a pre-trained model (like VGG16 / MobileNet / ResNet) is used to improve accuracy and reduce training time.

🚀 Objective

Build a binary image classifier (Dog vs Cat)

Use transfer learning to improve performance

Reduce overfitting

Achieve high accuracy with fewer training epochs

🧠 Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib

Google Colab / Jupyter Notebook

📂 Dataset

Dataset contains images of:

Dogs 🐶

Cats 🐱

Images are divided into:

Training set

Validation set

Test set

Dataset preprocessing includes:

Image resizing

Normalization

Data augmentation (if applied)



🔍 Model Architecture

Pre-trained CNN base model (Transfer Learning)

Frozen convolution layers (initially)

Fully connected Dense layers

Dropout layer (to reduce overfitting)

Sigmoid activation (Binary Classification)

Loss Function:

Binary Crossentropy

Optimizer:

Adam

Evaluation Metric:



Accuracy
📊 Training Process

Load pre-trained model (without top layer)

Add custom classification layers

Freeze base model layers

Compile model

Train model on training dataset

Validate using validation dataset

Plot accuracy and loss graphs



📈 Results

Achieved high classification accuracy

Transfer learning significantly reduced training time

Model generalizes well on unseen data




🖼 Sample Output

Correct classification of dog and cat images
Future Improvements

Fine-tuning deeper layers

Hyperparameter tuning

Deploy model using Flask / Streamlit

Convert to web app
Accuracy & Loss graphs plotted after training



💡 Why Transfer Learning?

Saves training time

Works well with smaller datasets

Uses powerful pre-trained feature extractors

Improves accuracy



