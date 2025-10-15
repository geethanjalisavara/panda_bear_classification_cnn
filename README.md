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
- Saved trained model (`.h5`) can be loaded anytime without retraining

 🖥️ How to Run in Colab

1. Open the notebook [`panda_bear_classifier.ipynb`](panda_bear_classifier.ipynb) in Google Colab.  
2. Upload the dataset zip file (`archive (1).zip`) if required.  
3. Run all cells sequentially:  

   - **Step 1:** Extract dataset and check folder structure  
   - **Step 2:** Create ImageDataGenerators for training & validation  
   - **Step 3:** Build and compile the CNN model  
   - **Step 4:** Train the model (or load the saved model)  
   - **Step 5:** Test predictions on new images  

4. If you want to **use the pre-trained model**, download it from the repo:
from tensorflow.keras.models import load_model

model = load_model("panda_bear_classifier.keras") 

📦 Requirements
Python 3.x
TensorFlow 2.x
Keras
Google Colab (recommended)

You can install any missing packages using pip:
!pip install tensorflow keras


📈 Notes
The model is simple and trained on a small dataset — accuracy may decrease on very different images.
For production or deployment, a larger dataset and more complex model is recommended.


🏆 Author
Geethanjali Savara



