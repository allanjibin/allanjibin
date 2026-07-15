# Hi there, I'm Alan! 👋

I'm a **B.Tech student** at St. Joseph's College of Engineering and Technology, Palai. I build at the intersection of hardware and software, currently focused on **Network Security**, **IoT Intrusion Detection**, and applied **Machine Learning**.

Currently interning as a **Network Security Intern at IIIT Kottayam**, researching ML-based intrusion detection for MQTT and encrypted QUIC traffic — work targeting a SECRYPT 2026 submission.

🔗 Portfolio: [allanjibin.github.io/alan-jibin-portfolio](https://allanjibin.github.io/alan-jibin-portfolio/)

---

## 🛠️ Tech Stack & Tools

![Python](https://img.shields.io/badge/-PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Arduino](https://img.shields.io/badge/-ARDUINO-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-SCIKIT--LEARN-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Wireshark](https://img.shields.io/badge/-WIRESHARK-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)

- **Security & Networking:** Network Security, Intrusion Detection Systems (IDS), MQTT/QUIC Protocol Analysis, Wireshark, GRC
- **Machine Learning:** Scikit-learn, XGBoost, TensorFlow, Feature Selection, Class Imbalance Handling (SMOTE), YOLOv8, OpenCV
- **Hardware:** ESP32, NodeMCU, Sensors (IMU, Flex, Gas)
- **Cloud:** AWS Foundations

---

## 🚀 Featured Projects

### 🔐 MQTT-Based IoT Intrusion Detection
*Research — targeting SECRYPT 2026*
- **The Problem:** MQTT-based IoT networks are highly vulnerable to flooding and malformed-packet attacks, and existing detection models struggle with class imbalance.
- **The Solution:** Built an end-to-end ML pipeline on the BCCC-IoT-MQTT-IDS-2025 dataset (6.2M+ records), comparing 6 classifiers across 2 balancing strategies and 3 train/test splits (36 total configurations).
- **Result:** Random Forest on a downsampled 80:20 split achieved 87.71% accuracy / 0.8771 F1-score.
- **Tech:** Python, Scikit-learn, XGBoost, Pandas

### 🔒 Unsupervised Zero-Day Detection in Encrypted QUIC Traffic
*Ongoing research*
- **The Problem:** QUIC's encryption blocks traditional payload-inspection IDS techniques, and zero-day attacks have no known signature to match.
- **The Solution:** Researching an Isolation Forest-based unsupervised anomaly detector using encrypted flow-level metadata alone.
- **Tech:** Python, Unsupervised ML, Isolation Forest

### 🦾 Automated Metal Chain Crack Detection System
- **The Problem:** Manual inspection of industrial chains is slow and prone to human error.
- **The Solution:** Developed a real-time detection rig using YOLOv8 to identify surface deformations and cracks.
- **Tech:** Python, OpenCV, PyTorch, custom hardware rig

### 🧤 Assistive Haptic Glove for Gesture Recognition
- **The Problem:** Limited communication tools for individuals with speech or motor impairments.
- **The Solution:** A wearable glove that translates hand gestures into digital commands or speech using homemade flex sensors and IMUs.
- **Tech:** ESP32, Flex sensors, IMUs

---

## 📍 Currently

- 🔭 Researching MQTT & QUIC intrusion detection at **IIIT Kottayam**
- 🎓 B.Tech in Electronics & Computer Engineering, Class of 2027
- 🌐 Google Student Ambassador
- 📫 Reach me on [LinkedIn](https://www.linkedin.com/in/alan-jibin-b5aa36253)
