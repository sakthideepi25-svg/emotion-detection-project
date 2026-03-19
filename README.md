
# 😊 Emotion Detection from Facial Expressions Using Deep Learning

A Vision Transformer (ViT) based multi-head deep learning framework for accurate facial emotion recognition with integrated face recognition support.

---

## 📌 Project Overview

This project proposes a **Vision Transformer (ViT) based multi-head deep learning framework** that focuses on accurate face emotion recognition while supporting face recognition as an additional feature.

The ViT backbone divides facial images into patches and employs **self-attention mechanisms** to learn global facial representations, enabling reliable detection of subtle and complex emotional patterns.

---

## 🎯 Features

- ✅ Real-time emotion detection from images and video
- ✅ Multi-class facial emotion classification (Happy, Sad, Angry, Fear, Surprise, Disgust, Neutral)
- ✅ Integrated face recognition using identity embeddings
- ✅ Multi-task learning architecture (single unified model)
- ✅ Web dashboard using Flask
- ✅ Emotion history stored in MySQL database
- ✅ Responsive UI using HTML, CSS, Bootstrap

---

## 🛠️ Technologies Used

| Category | Tools |
|----------|-------|
| Language | Python 3.9+ |
| Deep Learning | TensorFlow / PyTorch |
| Model Architecture | Vision Transformer (ViT) |
| Web Framework | Flask |
| Frontend | HTML, CSS, Bootstrap |
| Database | MySQL |
| Image Processing | OpenCV, Pillow |
| Data Analysis | NumPy, Pandas, Scikit-learn, Matplotlib |

---

## 🧠 System Architecture

### Modules

1. **Face Emotion Analyzer** — Core module integrating frontend, backend, database, and deep learning
2. **System User Module** — Admin and Registered User roles with authentication
3. **Model Development**
   - Data Collection & Preprocessing
   - Vision Transformer Architecture Design
   - Model Training & Optimization
   - Model Evaluation & Validation
4. **Facial Emotion Predictor** — Real-time/image-based emotion classification
5. **Face Identity Predictor** — Identity embedding comparison for personalization
6. **Result Visualization** — Dashboard with graphs and emotion trend charts

---

## ⚙️ System Requirements

### Hardware
- Processor: Intel i5 / AMD Ryzen 5 or equivalent
- RAM: 16 GB or higher
- Storage: 512 GB SSD (recommended)

### Software
- OS: Windows 10 / Windows 11
- Python 3.9 or above
- MySQL Database
- Wamp Server

---

## 🚀 How It Works

1. User uploads an image or uses live camera input
2. Face detection isolates the facial region
3. Image is divided into fixed-size patches (ViT approach)
4. Self-attention mechanisms capture global facial relationships
5. **Primary head** → Predicts emotion category
6. **Secondary head** → Generates identity embeddings
7. Results displayed on web dashboard and stored in database

---

## 📊 Emotion Categories

| Emotion | Description |
|---------|-------------|
| 😊 Happy | Positive emotional state |
| 😢 Sad | Low emotional state |
| 😠 Angry | Negative high-arousal state |
| 😨 Fear | Fearful expression |
| 😲 Surprise | Unexpected reaction |
| 😒 Disgust | Aversion expression |
| 😐 Neutral | No specific emotion |

---

## 💡 Advantages Over Existing Systems

- ✅ Global feature learning (vs. CNN's local features)
- ✅ Robust to lighting and pose variations
- ✅ Higher accuracy for subtle emotions
- ✅ Single unified model reduces complexity
- ✅ Real-time performance
- ✅ Personalization through face recognition

---

## 👩‍💻 Author

**Deepika S**  
Master of Computer Applications (MCA)  
Muthayammal Engineering College, Rasipuram  
Anna University (Autonomous)  

---

## 📄 License

This project is for academic purposes.
