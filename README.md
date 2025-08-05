# Lung-Disease-Classification-

---
## 🔍 Overview

This project presents a robust deep learning solution to classify **lung diseases** from chest X-ray images into four categories:

* 🦠 **COVID-19**
* 🫀 **Normal**
* 🤒 **Pneumonia**
* 🧬 **Tuberculosis**

Using **Transfer Learning** with the **VGG16** architecture, this model was trained and deployed via a local web application to enable real-time predictions, empowering medical analysis through AI.

---

## 🎯 Project Highlights

### 🧼 1. **Image Preprocessing & Augmentation**

✅ Cleaned and normalized raw chest X-ray images
✅ Resized images to match model input dimensions (224×224)
✅ Applied data augmentation techniques to boost generalization:

* Rotation
* Zoom
* Horizontal Flip
* Shear Transform

This helped reduce overfitting and increase dataset variability.

---

### 🧠 2. **Transfer Learning with VGG16**

Used **VGG16** (pre-trained on ImageNet) as the feature extractor.

🔧 **Custom Classification Layers** added:

* `Flatten`
* `Dense` layers with ReLU activation
* `Dropout` for regularization
* Final `Dense` with **Softmax** for multi-class output (4 classes)

Transfer learning drastically reduced training time and improved performance on limited data.

---

### 💻 3. **Local Web Application**

🚀 Built an intuitive, lightweight interface using **Flask** (or **Streamlit**) where users can:

* Upload X-ray images
* Get instant predictions (COVID-19 / Normal / Pneumonia / TB)
* View results directly on-screen

The app is fully containerizable and runs locally without needing cloud deployment.

---

### 📊 4. **Model Evaluation**

Ensured balanced and reliable performance using the following metrics:

| Metric                  | Purpose                                 |
| ----------------------- | --------------------------------------- |
| 📉 **Confusion Matrix** | Analyzes correct vs. misclassifications |
| 🎯 **Precision**        | Measures class prediction accuracy      |
| ♻️ **Recall**           | Measures detection completeness         |
| 🧮 **F1-Score**         | Balances precision & recall             |

The model showed **high accuracy** and strong handling of class imbalance, especially in detecting critical diseases like COVID-19 and Pneumonia.

---

## 🛠️ Tech Stack

| Category         | Tools & Libraries                          |
| ---------------- | ------------------------------------------ |
| 🐍 Language      | Python 3.x                                 |
| 🔍 Deep Learning | TensorFlow, Keras (VGG16, Dense, Dropout)  |
| 📈 ML Metrics    | Scikit-learn (confusion matrix, precision) |
| 🖼️ Image Prep   | OpenCV, PIL, ImageDataGenerator            |
| 🌐 Web UI        | Flask / Streamlit                          |

---

## 🧪 Future Improvements

* 🌐 Deploy the app on the cloud (e.g., Heroku, Render)
* 📲 Make it mobile-responsive
* 🧠 Integrate Grad-CAM for X-ray heatmap visualization
* 🔄 Auto-update model with new training samples (semi-supervised learning)

---

## 🙋‍♂️ Author

**Bhanu Prakash Achini**
📧 [bhanuprakashachini08@gmail.com](mailto:bhanuprakashachini08@gmail.com)

---

