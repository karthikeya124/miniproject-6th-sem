# 🚨 Fight Alert System using Deep Learning (LRCN)

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&duration=3500&pause=1000&color=FF3B3B&center=true&vCenter=true&width=900&lines=Fight+Alert+System;Real-Time+Violence+Detection;Deep+Learning+%7C+LRCN+Model;AI-Powered+Surveillance+System" />
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange?style=for-the-badge&logo=tensorflow)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-green?style=for-the-badge&logo=opencv)
![LRCN](https://img.shields.io/badge/LRCN-CNN+%2B+LSTM-red?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Accuracy-95.6%25-brightgreen?style=for-the-badge)

</p>

---

# 🚀 Project Highlights

- 🛡️ Real-time fight detection from surveillance videos
- 🎥 Deep Learning based LRCN architecture
- 🧠 CNN + LSTM for spatial and temporal feature learning
- 🚨 Instant alert generation on violence detection
- 📊 Achieved **95.6% Accuracy**
- 🏫 Suitable for schools, malls, offices, and public places

---

# 📖 Overview

Manual monitoring of CCTV footage is inefficient and prone to human error, especially in crowded environments.

The **Fight Alert System** is an AI-powered surveillance solution that automatically detects violent activities from surveillance videos using a **Long-term Recurrent Convolutional Network (LRCN)** architecture.

The system combines:

- CNN for spatial feature extraction
- LSTM for temporal sequence learning
- Real-time prediction
- Automatic alert generation

This significantly reduces monitoring effort while improving public safety.

---

# 🎯 Applications

- 🏫 Schools & Colleges
- 🏢 Offices
- 🛒 Shopping Malls
- 🚉 Railway Stations
- ✈ Airports
- 🏟 Stadiums
- 🏥 Hospitals
- 🚓 Smart City Surveillance

---

# 📂 Dataset

The model is trained using surveillance video datasets containing multiple human activities.

| Property | Value |
|----------|--------|
| Data Type | Videos |
| Classes | Fighting, Walking, Running |
| Input | Video Frames |
| Processing | Frame Extraction |
| Model | LRCN |

---

# 🏗 Proposed Architecture

```
Input Video
      │
      ▼
Frame Extraction
      │
      ▼
Image Preprocessing
      │
      ▼
CNN Feature Extraction
      │
      ▼
LSTM Temporal Learning
      │
      ▼
Fully Connected Layer
      │
      ▼
Fight / Non-Fight Prediction
      │
      ▼
Alert Generation
```

---

# ⚙ Methodology

```text
Surveillance Video
        │
        ▼
Frame Extraction
        │
        ▼
Resize & Normalize
        │
        ▼
CNN
        │
        ▼
LSTM
        │
        ▼
Dense Layer
        │
        ▼
Softmax Classification
        │
        ▼
Fight Detection
        │
        ▼
Alert Generation
```

---

# 🧠 Model Components

| Module | Purpose |
|---------|---------|
| Frame Extraction | Video Processing |
| CNN | Spatial Feature Extraction |
| LSTM | Motion Analysis |
| Dense Layer | Classification |
| Alert Module | Notification Generation |

---

# 🛠 Technologies Used

- Python
- TensorFlow
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

# ⚙ Experimental Setup

| Parameter | Value |
|-----------|-------|
| Training Dataset | 80% |
| Testing Dataset | 20% |
| Framework | TensorFlow |
| Input | Video Frames |
| Hardware | Intel Core i5, 8GB RAM |

---

# 📊 Performance

| Model | Accuracy | Precision | Recall |
|--------|----------|-----------|--------|
| Model 1 | 92.4% | 91.8% | 93.0% |
| Model 2 | 89.1% | 88.5% | 90.2% |
| ⭐ Proposed LRCN | **95.6%** | **95.1%** | **96.0%** |

---

# 📂 Repository Structure

```
Fight-Alert-System
│
├── README.md
├── Fight_Alert_System.ipynb
├── dataset/
├── models/
├── images/
├── results/
├── requirements.txt
└── Report.pdf
```

---

# ▶️ Installation

```bash
git clone https://github.com/yourusername/Fight-Alert-System.git

cd Fight-Alert-System

pip install -r requirements.txt
```

---

# ▶️ Run the Project

```bash
jupyter notebook Fight_Alert_System.ipynb
```

or

```bash
python app.py
```

---

# 📈 Future Enhancements

- YOLO-based person detection
- Vision Transformers (ViT)
- Real-time CCTV integration
- Mobile Notifications
- Cloud Deployment
- Edge AI Deployment
- Multi-camera Monitoring
- Audio-based Violence Detection

---

# 👨‍💻 Team Members

**P. Karthikeya**

**G. Shravan Kumar**

**P. Naga Rupesh**

Department of Artificial Intelligence & Machine Learning

Chaitanya Bharathi Institute of Technology (CBIT)

Hyderabad, India

---

# 🙏 Acknowledgements

- Department of AI & ML, CBIT
- Dr. K. Mary Sudha Rani
- TensorFlow
- OpenCV
- Deep Learning Community

---

<p align="center">

⭐ If you found this project useful, please consider giving it a Star.

Made with ❤️ by Team Fight Alert System

</p>
