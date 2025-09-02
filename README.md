**Lung Disease Classification**

Lung Disease Classification is a deep learning project that classifies chest X-ray images into four categories: Normal, COVID-19, Pneumonia, and Tuberculosis. The system is designed to help healthcare professionals detect lung diseases early and accurately using advanced deep learning techniques.

**Features**

This project uses a multi-channel EfficientNet ensemble (EfficientNetB0, B1, and B2) to classify chest X-ray images into four lung disease categories. To make the model more robust and reliable, it employs advanced data augmentation, regularization techniques, early stopping, and adaptive learning rates, which help improve accuracy while preventing overfitting. The system not only demonstrates random prediction examples from the dataset but also allows users to test their own uploaded X-ray images for instant disease classification. To make the model’s decisions more transparent, LIME explanations highlight the specific regions of the X-ray that influenced each prediction. With these strategies, the model achieves 96% training accuracy and 93% validation accuracy, providing a strong and dependable tool for lung disease detection.

**Dataset**

Total Images: 7,135 chest X-ray images

Classes: Normal, COVID-19, Pneumonia, Tuberculosis

Source: https://www.kaggle.com/datasets/jtiptj/chest-xray-pneumoniacovid19tuberculosis

**Tech Stack**

Python with TensorFlow / Keras

Scikit-learn for ensemble and evaluation

Matplotlib & Seaborn for visualization

LIME for model explanation
