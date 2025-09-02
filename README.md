**Lung Disease Classification**

Lung Disease Classification is a deep learning project that classifies chest X-ray images into four categories: Normal, COVID-19, Pneumonia, and Tuberculosis. The system is designed to help healthcare professionals detect lung diseases early and accurately using advanced deep learning techniques.

Features

Multi-class classification using a multi-channel EfficientNet ensemble (EfficientNetB0, B1, B2).

Advanced data augmentation, regularization, early stopping, and learning rate scheduling for improved model performance.

Random prediction examples from the dataset for visualization of model behavior.

Uploaded image prediction: Users can provide their own X-ray images for instant disease classification.

LIME explanations: Visual interpretability of predictions, showing which regions influenced the model’s decision.

Achieved 96% training accuracy and 93% validation accuracy.

Dataset

Total Images: 7,135 chest X-ray images

Classes: Normal, COVID-19, Pneumonia, Tuberculosis

Source: Chest X-ray – Pneumonia, COVID-19, Tuberculosis (Tipirneni, 2022)
 [1]

Tech Stack

Python with TensorFlow / Keras

Scikit-learn for ensemble and evaluation

Matplotlib & Seaborn for visualization

LIME for model explanation
