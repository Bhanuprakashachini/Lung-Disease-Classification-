# Lung-Disease-Classification-

    Built a deep learning model using VGG16 to classify lung diseases (COVID-19, Normal, Pneumonia, Tuberculosis). Pre-processed and augmented image data for training and integrated a pre-trained VGG16 model with custom classification layers. Deployed the model in a web application to run locally on a computer, enabling real-time predictions through a user interface. Achieved high accuracy and evaluated the model using confusion matrix, precision, recall, and F1-score. Technologies: Python, TensorFlow, Keras, Scikit-learn. Project Highlights ✅ Image Preprocessing & Augmentation: The input dataset was cleaned, resized, normalized, and augmented (rotation, zoom, horizontal flip, etc.) to increase model robustness and reduce overfitting.

🧠 Transfer Learning with VGG16: A pre-trained VGG16 model (trained on ImageNet) was used as the base. The top layers were replaced with a custom classifier including Dense, Dropout, and Softmax layers to output predictions for the 4 classes.

💻 Local Web Application: The trained model was integrated into a web-based interface using libraries like Flask or Streamlit, allowing users to upload X-ray images and receive real-time disease predictions.

📊 Model Evaluation: Model performance was assessed using:

Confusion Matrix

Precision

Recall

F1-Score These metrics ensured that the model didn’t just perform well overall but also handled class imbalances and critical errors effectively.
