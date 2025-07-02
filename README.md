# 🌾 Rice Leaf Disease Detection

This project presents a **deep learning-based solution** for detecting and classifying three major rice leaf diseases: **Bacterial Leaf Blight**, **Brown Spot**, and **Leaf Smut**. Developed as the **capstone project** for a Data Science internship, it applies transfer learning and custom CNN architectures to address a real-world agricultural challenge.

---

## 🎯 Objectives

- Develop a CNN model to detect leaf diseases in rice crops.
- Utilize a balanced but limited dataset efficiently.
- Improve model generalization using preprocessing and data augmentation.
- Evaluate performance using validation accuracy, confusion matrix, and classification reports.

---

## 🧠 Model Highlights

- ✅ Hybrid model: combination of **pretrained CNNs** (e.g., VGG16) and custom layers.
- 📊 Accuracy:  
  - Training Accuracy: **83.33%**  
  - Final Validation Accuracy: **75%**
- 🧪 Evaluation: Confusion matrix reveals strong classification performance, with minor confusion between visually similar classes.

---

## 🛠️ Tech Stack

- Python 3.8+
- TensorFlow / Keras
- OpenCV, Matplotlib, NumPy
- Jupyter Notebook / Google Colab

---

## 📂 Project Structure

```
.
├── Data/
│   ├── Bacterial leaf blight/
│   ├── Brown spot/
│   └── Leaf smut/
├── Rice Leaf Disease Detection.ipynb         # Main training notebook
├── README.md
```

---

## 🚀 Getting Started

1. **Clone the Repository**

```bash
git clone https://github.com/Jay-CodeHub/Rice-Leaf-Disease-Detection.git
cd Rice-Leaf-Disease-Detection
```

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Model**

Open the notebook:

```bash
jupyter notebook Rice Leaf Disease Detection.ipynb
```

Train or test the model using provided cells and dataset structure.

---

## 🔍 Evaluation Metrics

- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-score)
- **Loss & Accuracy Curves**
- Clear separation of classes with occasional overlap due to visual similarity in symptoms.

---

## 🌿 Outcome

This project demonstrates the potential of **deep learning for early, automated crop disease detection**, especially in resource-constrained environments. With real-time deployment, such models can help improve agricultural productivity and reduce losses.




