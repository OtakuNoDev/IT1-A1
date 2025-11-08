# IT1-A1
This repo contains all the contents related to out CEP


## Contents :
1. All reviews ppt
2. Review
3. Video with voice

# 🧠 EduBridge
### _A Low-Bandwidth Virtual Classroom Ecosystem for Rural Education_

---

## 🚩 Problem Statement

Rural diploma colleges often lack subject lecturers in advanced domains such as **Artificial Intelligence**, **VLSI**, and **Renewable Energy**.  
Students are left to depend on self-study or costly city-based coaching, widening the **urban-rural learning gap**.

Existing online education solutions fail due to **unstable, low-bandwidth connectivity** and the need for **complex infrastructure**.  
There is a critical need for a **lightweight, software-only virtual classroom ecosystem** that ensures:
- Clear audio and compressed visuals  
- Offline-accessible recordings  
- Interactive quizzes and discussion boards  
- Optimized performance for entry-level smartphones and minimal data usage  

The solution must be **simple for faculty**, **affordable for institutions**, and **sustainable in low-resource environments**.

---

## 🎯 Objectives

- Develop a **low-bandwidth optimized virtual classroom system**.  
- Ensure **audio-first delivery** with compressed visuals for clarity.  
- Provide both **live interaction** and **offline access** to lectures.  
- Enable **interactive features** (quizzes, polls, discussion boards).  
- Design a **mobile-friendly**, **simple**, and **cost-effective** solution.

---

## 💡 Proposed Solution

**EduBridge** is a **software-only virtual classroom platform** designed to deliver seamless learning experiences in low-connectivity environments.  
It enables **real-time interaction**, **recorded sessions**, and **AI-based engagement monitoring**, without requiring expensive hardware or high-speed internet.

---

## 🧰 Technology Stack

**Frontend:** React.js, Tailwind CSS, TypeScript  
**Backend:** Express.js  
**Database:** PostgreSQL  
**Machine Learning Framework:** TensorFlow + Keras (trained on Kaggle)

**Dataset Details:**
- Custom 2-class dataset: `Engagement` and `Disengagement`
- Total Images: 8000  
- Preprocessing: Resized to 224×224, pixel values rescaled to [0,1]  
- Split: 80% Training, 20% Validation  

**Models Tested:**  
- ✅ MobileNetV2 (Selected)  
- 🔵 ResNet50  
- 🔴 VGG16  

🔗 [Kaggle Notebook](https://www.kaggle.com/code/imgojo/face-engagement)  
🔗 [Keras Model Reference](https://keras.io/api/applications/)

---

## ⚙️ Why MobileNetV2?

- Designed for **low-compute, low-power environments**  
- Requires **less memory and processing time**  
- Offers **real-time performance** on entry-level devices  
- Ideal for **mobile and rural classroom deployments**

---

## 👥 Contributors

- **Gaurav Jadhav (SI154)**  
- **Shreyash Mandlapure (SI167)**  

**Guide:** Mrs. S. P. Vanjari  
Department of Information Technology  
Marathwada Mitra Mandal’s College of Engineering, Pune

---
