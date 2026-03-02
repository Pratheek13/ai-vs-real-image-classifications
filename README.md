# ai-vs-real-image-classification

## 📖 Project Overview
This project focuses on classifying images as **AI-generated** or **Real photographs** using deep learning models.  
The goal is to evaluate how effectively different CNN architectures can detect synthetic images and compare their performance.

The models were trained and evaluated on a balanced dataset of 1,426 test images.

---

## 🎯 Objectives
- Classify images into AI-generated and Real categories
- Compare performance of multiple CNN models
- Analyze misclassification patterns
- Evaluate models using accuracy, precision, recall, F1-score, and confusion matrix

---

## 🧠Models Used
- ResNet50
- MobileNetV2
- EfficientNetB0

All models were implemented and fine-tuned using PyTorch for binary classification.

---

## 🗂 Dataset
Test Set Distribution:
- AI Images: 744
- Real Images: 682
- Total Test Images: 1426

Images were resized, normalized, and augmented before training.

---

## ⚙️ Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Final Results

### 🔹 MobileNetV2
- Test Accuracy: **98.81%**
- Confusion Matrix:
```
[[736   8]
 [  9 673]]
```

### 🔹 ResNet50
- Test Accuracy: **98.81%**
- Confusion Matrix:
```
[[735   9]
 [  8 674]]
```

### 🔹 EfficientNetB0
- Test Accuracy: **97.27%**
- Confusion Matrix:
```
[[717  27]
 [ 12 670]]
```

---

## 📈 Performance Comparison

| Model         | Accuracy |
|--------------|----------
| MobileNetV2  | 98.81%    |
| ResNet50     | 98.81%    |
| EfficientNet | 97.27%    |

---

## 🔎 Observations
- MobileNetV2 and ResNet50 achieved the highest accuracy (98.81%).
- EfficientNetB0 showed slightly lower performance (97.27%).
- All models performed strongly on both AI and Real classes.
- Misclassification rate was very low across models.
- The dataset appears well-balanced and clean.

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/ai-vs-real-image-classification.git
cd ai-vs-real-image-classification
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Train the Model
```bash
python train.py
```

### 4️⃣ Test the Model
```bash
python test.py
```

---

## 📌 Future Improvements
- Test on larger and more diverse datasets
- Evaluate robustness against image compression and editing
- Implement Vision Transformers (ViT)
- Deploy as a web-based detection tool

---

## 👤 Author
Pothuri Indraneel  
B.Tech – Computer Science & Engineering  
