# 🐱🐶 Cat vs Dog Image Classifier using CNN

This project implements an image classification model using a **Convolutional Neural Network (CNN)** to distinguish between images of **cats** and **dogs**. Built with TensorFlow and Keras, this deep learning pipeline demonstrates core computer vision techniques such as **data augmentation**, **training visualization**, and **evaluation with metrics**.

---

## 🚀 Project Highlights

- 📦 Dataset: Folder of cat and dog images, organized by class
- 🧠 Model: Custom CNN built from scratch
- 🧪 Validation: Accuracy/loss curves, confusion matrix, classification report
- 🖼️ Output: Predicted labels overlaid on test samples
- 📈 Monitoring: tqdm progress bar and visual feedback

---

## 🛠️ Tech Stack

- Python 3.x
- TensorFlow & Keras
- OpenCV (image preprocessing)
- Matplotlib & Seaborn (visualization)
- tqdm (progress bar)

---

## 📁 Project Structure

```
New folder (4)/
├── README.md
├── requirements.txt
├── notebooks/
│   ├── cat_dog_cnn.ipynb       # Main Jupyter notebook
│   ├── models/                 # Saved model files (.keras)
│   └── outputs/                # Visual outputs (plots, predictions)
```

> 📂 Dataset directory should be placed at the same level as `notebooks/`:
```
dataset/
├── training_set/
│   ├── cats/
│   └── dogs/
└── test_set/
    ├── cats/
    └── dogs/
```

---

## ▶️ Getting Started

1. **Install dependencies**:
```bash
pip install -r requirements.txt
```

2. **Prepare your dataset** as shown above.

3. **Run the notebook**:
```bash
jupyter notebook notebooks/cat_dog_cnn.ipynb
```

---

## 📊 Sample Results

- ✅ Model Accuracy: ~90%+
- 📈 Accuracy/Loss Curves saved in `outputs/accuracy_loss.png`
- 📊 Confusion Matrix in `outputs/confusion_matrix.png`
- 🐶 Sample Predictions in `outputs/sample_predictions.png`

---

## 🔮 Future Enhancements

- Use **transfer learning** (e.g., VGG16, ResNet)
- Deploy via **Streamlit** or **Flask** web app
- Add **real-time webcam classification**

---

## 📬 Connect with Me

**Ahsan Ali**  
📧 Email: _[aa6797331@gmail.com]_  
🔗 LinkedIn: _[www.linkedin.com/in/ahsan-ali-b3a22a319]_  
💻 GitHub: _[[https://github.com/AhsanAli-AI]

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify for your own learning or applications.
