# Week-1
Plastic Waste Image Classification using CNN This project focuses on building a Convolutional Neural Network (CNN) model to classify images of plastic waste into predefined categories (e.g., plastic bottles, bags, etc.). The goal is to leverage deep learning to aid in waste management and recycling efforts by automating the classification process.
Key Topics
1. Project Planning
Objective Definition: Understand the problem statement and define measurable goals (e.g., classify plastic waste images into categories).
Dataset Selection: Identify and evaluate datasets that align with the project requirements.
Project Workflow: Learn the step-by-step flow: data collection → preprocessing → model building → evaluation → deployment.
2. Importing
Import necessary libraries like TensorFlow, NumPy, Matplotlib, etc.
Load datasets from local storage, online repositories, or APIs.
Set up directories for training, validation, and testing datasets.
3. Pre-Processing
Data Cleaning: Handle missing data, outliers, and inconsistencies in the dataset.
Normalization and Rescaling: Scale image pixel values to a range of 0-1 for better model performance.
Data Augmentation: Enhance dataset variety using techniques like flipping, rotation, zooming, and shifting.
Prepare data generators to handle batches for training and testing efficiently.
4. Data Modeling
Build a simple Convolutional Neural Network (CNN) architecture to classify images.
Define layers, activation functions, and output shapes based on the dataset.
Compile the model using appropriate loss functions and optimizers (e.g., categorical cross-entropy and Adam).
