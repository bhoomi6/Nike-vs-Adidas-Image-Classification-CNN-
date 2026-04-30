# 👟 Nike vs Adidas Image Classification (CNN)

## 📌 Project Overview

This project uses a Convolutional Neural Network (CNN) to classify images of shoes into two categories:

* Nike
* Adidas

The model learns visual patterns from grayscale images and predicts the brand based on features.

---

## 🧠 Model Architecture

* Convolutional Neural Network (CNN)
* Multiple Conv2D layers (32, 64 filters)
* MaxPooling layers for feature reduction
* Flatten layer to convert feature maps into vectors
* Dense layers for classification
* Output layer with Softmax activation (2 classes)

---

## ⚙️ Technologies Used

* Python
* NumPy
* Keras / TensorFlow
* PIL (Image Processing)
* Matplotlib
* tqdm (progress tracking)

---

## 📂 Dataset

* Custom dataset of shoe images
* Images labeled as:

  * NIKE
  * ADIDAS
* Preprocessing steps:

  * Converted to grayscale
  * Resized to 120x120 pixels
  * Normalized pixel values (0–1)

---

## 🔄 Workflow

1. Load images from directory
2. Assign labels based on filename
3. Convert images to grayscale
4. Resize and normalize images
5. Train CNN model
6. Predict brand for new images

---

## 🧪 Sample Prediction

Input: Shoe image
Output:

* [1, 0] → Nike
* [0, 1] → Adidas

---

## ▶️ How to Run

```bash
pip install numpy matplotlib pillow tensorflow keras tqdm
python model.py
```

---

## 📌 Important Note

The dataset path used in this project is from Google Colab:

```
/content/sample_data/
```

You may need to update paths when running locally.

---

## 📈 Future Improvements

* Add train-test split
* Increase dataset size for better accuracy
* Use color images instead of grayscale
* Add model evaluation metrics (confusion matrix, precision, recall)
* Deploy as a web app using Flask

---

## 💡 Key Learning

* Understanding CNN architecture
* Image preprocessing techniques
* Feature extraction using convolution layers
* Model training and prediction
