# Vision-Based Fall Detection Using Deep Learning  
### MSc Project — Sumit Shekhar Mishra (23419CMP027)  
### Institute of Science, Banaras Hindu University

This project presents a **vision-based fall detection system** developed as part of the MSc (Computer Science) program.  
The work focuses on building a robust system using **MediaPipe Pose**, **LSTM networks**, and **video frame landmark analysis**.

---

## 📌 Project Overview
The aim of this project is to detect fall events using deep learning by analyzing human pose landmarks extracted from video frames.

Two major steps are followed:

### **1. Pose Landmark Extraction**  
MediaPipe is used to extract **33 pose landmarks** for every frame in the video.

### **2. Temporal Motion Learning (LSTM Model)**  
An LSTM-based model is trained on sequences of landmarks  
to identify motion patterns that represent falls.

---

## 📄 Files Included in This Repository

| File | Description |
|------|-------------|
| **frame_landmark_detection** | Extracts frames from videos and detects MediaPipe pose landmarks |
| **landmark_data_manipulation** | Cleans, interpolates, and structures landmark sequences for training |
| **landmark_lstm** | Contains the LSTM model used for fall detection |

---

## 🧠 Technologies Used
- **Python**
- **MediaPipe Pose**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy / Pandas**

---

## 📊 Summary of Workflow
1. Extract frames from videos  
2. Use MediaPipe to extract pose landmarks  
3. Preprocess, clean, and interpolate missing points  
4. Create sequences of 16 consecutive frames  
5. Train an LSTM model for fall vs non-fall classification  

---

## 🎯 Project Objectives
- Develop a fall detection pipeline using vision-based methods  
- Explore MediaPipe pose landmarks for motion understanding  
- Build and evaluate an LSTM-based deep learning model  

---

## 📌 Conclusion
The project successfully demonstrates how pose-based temporal modeling  
using LSTM can effectively detect human falls in video sequences.

---

## 🙌 Acknowledgements
This project was completed as part of the MSc coursework under the  
Department of Computer Science, Institute of Science, BHU.
