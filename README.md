LinkedIn Post:
# Fashion-MNIST-FCNN
End-to-end Deep Learning project to classify fashion images using a Fully Connected Neural Network.
# Fashion MNIST Classification using FCNN
# Overview
This project focuses on building a Fully Connected Neural Network (FCNN) to classify images from the Fashion MNIST dataset into 10 categories.
# Dataset
- 60,000 training images
- 10,000 testing images
- Image size: 28x28 grayscale
- 10 classes (T-shirt, Trouser, Sneaker, etc.)
# Steps Performed
1.Data Preprocessing
- Normalized pixel values (0–1)
- One-hot encoded labels
- 
2. Model Architecture
- Input: Flatten layer (28x28)
- Hidden Layers: Dense layers with ReLU activation
- Dropout for regularization
- Output Layer: 10 neurons with Softmax
3. Training
- Loss: Categorical Crossentropy
- Optimizer: Adam
- Callbacks: EarlyStopping, ReduceLROnPlateau
4. Evaluation
- Achieved ~86% validation accuracy
- Visualized loss and accuracy curves
# Result
- Model performs well with no overfitting
- Training and validation curves are aligned
# TechStack
- Python
- NumPy
- TensorFlow / Keras
- Matplotlib
# Conclusion
This project demonstrates a complete deep learning workflow and helped in understanding model training, evaluation, and optimization techniques.
