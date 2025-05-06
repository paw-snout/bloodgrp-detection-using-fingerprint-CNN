# 🩸Blood Group Detection using Fingerprint with CNN

This project leverages Convolutional Neural Networks (CNNs) to classify blood groups based on fingerprint images. It explores the feasibility of biometric patterns in predicting medical attributes.

# 📌Problem Statement

Traditional blood group identification requires invasive techniques. This project aims to utilize biometric fingerprints to classify a person’s blood group noninvasively using deep learning techniques.

# 🛠️Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas
- Matplotlib / Seaborn

# 🧪Model Architecture

The CNN architecture consists of:
- 3 Convolutional layers
- MaxPooling layers
- Flatten + Dense layers
- Softmax output for classification

See `src/model.py` for implementation details.

## 📊 Results

The model achieves high accuracy in classifying blood groups across multiple classes (A, B, AB, O; +ve/-ve).

| Class | Precision | Recall | F1-score |
|-------|-----------|--------|----------|
| A+    | 0.91      | 0.89   | 0.90     |
| B+    | 0.90      | 0.92   | 0.91     |
| ...   | ...       | ...    | ...      |

*Confusion matrix and additional metrics available in the `results/` folder.*

## 📁 Folder Structure

