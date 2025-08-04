# 📝 Handwritten Digit Recognition System

This project is designed to recognize handwritten notes using deep learning techniques. It converts handwritten text images into digital text using a trained neural network.

---

## 🏗️ System Architecture

      +-------------------+
      |   Input Image     |
      +-------------------+
               ↓
      +-------------------+
      | Preprocessing     |
      | (Grayscale, Resize|
      | Thresholding)     |
      +-------------------+
               ↓
      +-------------------+
      | Feature Extraction|
      | (Flatten Image)   |
      +-------------------+
               ↓
      +-------------------+
      | Neural Network /  |
      | CNN Model         |
      +-------------------+
               ↓
      +-------------------+
      | Predicted Text    |
      +-------------------+

---

## 🛠️ Required Libraries

| Library      | Purpose                                                                 |
|--------------|-------------------------------------------------------------------------|
| `tensorflow` | Building and training the deep learning model                           |
| `numpy`      | Numerical operations and array manipulation                             |
| `matplotlib` | Visualization of images and training progress                           |
| `opencv-python` | Image processing tasks like resizing, grayscale conversion, etc.    |
| `Pillow`     | Additional image loading/saving if needed                               |
| `sklearn`    | (Optional) Dataset splitting or evaluation metrics                      |

---

## ⚙️ Installation

Make sure you have Python 3.7+ installed.

1. Clone the repository:

```bash
git clone https://github.com/27104/HandWrittenDigitRecognition.git
cd HandWrittenDigitRecognition
```
## 📧 Contact

Email: sankaranagabalaji@gmail.com

GitHub: github.com/sankar27104
