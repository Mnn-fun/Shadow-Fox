
#  Image Classification Model — ShadowFox Task (Beginner)

##  Project Title:
**Image Tagging using CNN on CIFAR-10 Dataset**

## Objective

This project was developed as part of the **ShadowFox Beginner Task**, aimed at building a practical solution for **image tagging** using machine learning. The model is trained to classify input images into simple categories like **cat**, **dog**, **car**, etc., using a **Convolutional Neural Network (CNN)** built with **TensorFlow**.

---

##  What This Project Does

- Trains a CNN on the CIFAR-10 dataset  
- Categorizes images into 10 basic classes:
  ```
  ['airplane', 'automobile', 'bird', 'cat', 'deer', 
   'dog', 'frog', 'horse', 'ship', 'truck']
  ```
- Accepts uploaded images (via Google Colab)
- Predicts and displays the closest matching class label

---

##  Tools & Libraries Used

- Python
- TensorFlow / Keras
- NumPy
- Pillow (PIL)
- Google Colab (for user interaction and testing)

---

##  Dataset

We use the **CIFAR-10 dataset**, a well-known beginner-friendly image classification dataset containing:
- 60,000 color images (32×32 pixels)
- 10 classes
- 6,000 images per class

---

## How to Use

1. Open the project in **Google Colab**
2. Upload any image (JPEG/PNG, 3-channel RGB)
3. The model will:
   - Resize it to 32×32
   - Preprocess and normalize it
   - Predict the class
   - Print the top prediction

> ⚠Note: Real-world high-resolution photos are resized and may reduce model accuracy since the model is trained on small CIFAR-style images.

---

##  Model Architecture

- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten → Dense → Dropout
- Output Layer: Softmax

---

## Sample Output

```
 Predicted class: cat
```

---

## Credits

- Task provided by **ShadowFox - Learn • Create • Lead**
- Model built using TensorFlow in Python (Colab)
