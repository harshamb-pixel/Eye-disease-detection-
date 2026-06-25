# 👁️ Human Eye Disease Detection System using Deep Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red?logo=streamlit)
![OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-green?logo=opencv)
![License](https://img.shields.io/badge/License-Educational-blue)

## 📖 Overview

The **Human Eye Disease Detection System** is a Deep Learning-based web application that detects retinal diseases from **Optical Coherence Tomography (OCT)** images.

The application uses a **Convolutional Neural Network (CNN)** to classify retinal images into different disease categories while providing:

- Disease prediction
- Confidence score
- Image enhancement
- Disease localization
- Medical recommendations

The project is built using **Python, TensorFlow, OpenCV, and Streamlit**.

---

## 🚀 Features

- 🩺 Detect retinal diseases from OCT images
- 🧠 CNN-based image classification
- 📊 Confidence score prediction
- 🖼️ Image preprocessing pipeline
- ✨ CLAHE image enhancement
- 🎯 Disease region highlighting
- 📋 Disease recommendations
- 🌐 Interactive Streamlit Dashboard
- ⚡ Fast real-time predictions

---

# 🦠 Disease Classes

The model classifies OCT images into four categories:

| Class | Description |
|--------|-------------|
| CNV | Choroidal Neovascularization |
| DME | Diabetic Macular Edema |
| DRUSEN | Early Age-related Macular Degeneration |
| NORMAL | Healthy Retina |

---

# 🛠️ Tech Stack

## Programming Language

- Python

## Deep Learning

- TensorFlow
- Keras
- CNN (Convolutional Neural Network)

## Image Processing

- OpenCV
- NumPy
- Matplotlib

## Web Framework

- Streamlit

---

# 📂 Project Structure

```text
Eye-disease-detection-system/
│
├── app.py
├── recommendation.py
├── Trained_Eye_disease_model_v2.keras
├── output/
│   └── predicted_result.jpg
├── requirements.txt
├── README.md
└── assets/
    └── screenshots/
```

---

# 🔄 Workflow

```text
Input OCT Image
        │
        ▼
Image Preprocessing
(Resize + CLAHE + Enhancement)
        │
        ▼
CNN Deep Learning Model
        │
        ▼
Disease Prediction
        │
        ▼
Confidence Score
        │
        ▼
Disease Highlighting
        │
        ▼
Recommendation & Precautions
```

---

# 📸 Application Screenshots

## 🏠 Home Dashboard

![Home](assets/screenshots/home.png)

---

## 📤 Prediction Workspace

![Predict](assets/screenshots/predict.png)

---

## 📊 Prediction Result

![Result](assets/screenshots/result.png)

---

## 💊 Disease Recommendation

![Recommendation](assets/screenshots/recommendation.png)

---

# 📊 Model Performance

| Metric | Value |
|---------|------|
| Accuracy | 97% - 99% |
| Classes | 4 |
| Model | CNN |
| Input | OCT Images |
| Output | Disease Class + Confidence Score |

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Eye-disease-detection-system.git

cd Eye-disease-detection-system
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Linux/macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install streamlit tensorflow opencv-python matplotlib numpy
```

---

# ▶️ Run Application

```bash
streamlit run app.py
```

Open your browser:

```
http://localhost:8501
```

---

# 🧪 How to Use

1. Open the application.
2. Navigate to the **Predict** page.
3. Upload an OCT retinal image.
4. Click **Predict Disease**.
5. View:
   - Disease Name
   - Confidence Score
   - Enhanced Image
   - Disease Highlighting
   - Medical Recommendation

---

# 🎯 Advantages

- Early retinal disease detection
- High prediction accuracy
- Fast diagnosis
- User-friendly dashboard
- Medical recommendation support
- Useful for healthcare professionals
- Suitable for research and educational purposes

---

# 🔮 Future Enhancements

- 🔹 Support additional retinal diseases
- 🔹 Grad-CAM Explainable AI
- 🔹 Mobile Application
- 🔹 Cloud Deployment
- 🔹 Doctor Portal
- 🔹 Patient History Management

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

**Harsha M B**

- 🎓 Information Science & Engineering Student
- 💻 Passionate about AI, Machine Learning & Full Stack Development

GitHub:
https://github.com/YOUR_USERNAME

LinkedIn:
https://linkedin.com/in/YOUR_LINKEDIN

---

# 📜 License

This project is developed for **educational and research purposes** only.

---

⭐ If you found this project useful, don't forget to **Star ⭐ the repository**.
