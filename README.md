# 🧠 Co-Sign Language: AI-Powered Eye Communication System for ALS Patients

**Co-Sign Language** is a low-cost, AI-driven communication system designed to empower individuals with **Amyotrophic Lateral Sclerosis (ALS)** and severe motor impairments to communicate using only their eyes.  
Built as part of an independent research collaboration with **Cornell University (2024–2025)**, this project redefines accessibility through intelligent vision systems and ethical AI design.

---

## 🌍 Overview

Traditional assistive communication tools for ALS rely on expensive infrared or head-tracking sensors.  
Co-Sign Language introduces an affordable, **camera-based AI solution** that translates **intentional eye gestures into speech**, packaged in a wearable smart-glasses prototype costing **under $50**.

The system employs **Vision Transformers (ViT)** for gaze detection, **Kalman Filtering** for noise reduction, and an **NIS-based probabilistic model** to differentiate **intentional vs. unintentional** movements with exceptional precision.

---

## 🚀 Key Features
- 🔹 **98.8% gaze detection accuracy** validated across 3 diverse user groups (able-bodied, hearing-impaired, ALS patients).  
- 🔹 **20+ words per minute** real-time communication speed.  
- 🔹 **Ultra-low hardware cost (<$50)** using readily available components.  
- 🔹 **Lightweight architecture**, deployable on microcontrollers and Raspberry Pi.  
- 🔹 **Modular design**, allowing future integration with speech synthesis or translation models.

---

## 🧩 Technical Stack
- **Languages:** Python  
- **Frameworks & Libraries:** PyTorch, TensorFlow, OpenCV, NumPy, Pandas  
- **Model Architecture:** Vision Transformer (ViT), Kalman Filter, NIS-based classifier  
- **Environment:** Jupyter Notebook, Google Colab  
- **Prototype Deployment:** Raspberry Pi + 1080p camera module  

---

## 📊 Performance Summary

| Metric | Result | Description |
|--------|---------|-------------|
| Gaze Detection Accuracy | **98.8%** | On curated test dataset |
| Communication Speed | **20.4 WPM** | Real-time eye-to-speech synthesis |
| System Latency | **<100 ms** | Full inference pipeline |
| Comfort Rating | **9.2 / 10** | Based on user evaluation |

---

## 🧪 Experimental Setup
- **Participants:** 12 individuals (4 ALS, 4 hearing-impaired, 4 control).  
- **Conditions:** Varied lighting, fatigue, and motion interference.  
- **Objective:** Accurately classify gaze intent while minimizing strain and false positives.  

---

## 📚 Research Alignment
This project forms the foundation for an **ongoing publication** at **Cornell University**, to be submitted to **arXiv (2025)** in the Accessibility and AI for Healthcare category.  
It aligns directly with my long-term mission:  
> “To make AI not just automate — but equalize.”

---

## 🧑‍💻 Future Work
- 🧠 Expand to **multilingual eye-language** recognition via transfer learning.  
- 🔁 Implement **reinforcement learning** for personalized assistive communication.  
- 🧾 Release an **open-source dataset** for inclusive accessibility research.

---

## 🏅 Recognition
- 🥇 **4th Place Globally** – ISEF 2024, Systems Software Category  
- 🏆 **Best of Category (National Winner)** – Blastoff Software Competition 2024  
- 🥇 **Gold Medal** – EISTEF Software Competition 2024  
- 📺 **Recognized on Egyptian National TV** for innovation under resource-limited conditions  
- 💡 **Supported by mentorship from Cornell University AI researchers**

---

> *“At 2:07 a.m., the blink still confused the model — but I realized AI could do more than automate; it could give someone their voice back.”*
