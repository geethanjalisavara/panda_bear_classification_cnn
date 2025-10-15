 🐼 Panda vs Bear 🐻 Image Classifier

This is a simple Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify images as either **Pandas** or **Bears**. 
The model is trained on a small dataset and can predict new images directly in Google Colab.

📂 Repository Structure
panda_bear_classifier/
├── panda_bear_classifier.ipynb # Colab notebook with all code
├── panda_bear_classifier.h5 # Saved trained model
├── README.md


 ⚡ Features

- Preprocesses images using `ImageDataGenerator` (normalization & augmentation)
- Simple CNN architecture with two convolutional layers
- Trains on ~500 images and validates on ~100 images
- Predicts new images in a few lines of code
- Saved trained model (`.keras`) can be loaded anytime without retraining



📦 Requirements
Python 3.x
TensorFlow 2.x
Keras
Google Colab (recommended)

You can install any missing packages using pip:
!pip install tensorflow keras


📈 Notes
The model is simple and trained on a small dataset — accuracy may decrease on very different images.



🏆 Author
Geethanjali Savara



