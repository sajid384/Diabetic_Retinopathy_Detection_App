# 🩺 Diabetic Retinopathy Detection App

This project is an AI-powered mobile application that detects **Diabetic Retinopathy** (a diabetes-related eye disease) using a **pre-trained deep learning model**.  
Users can upload an image of their **retina (eye)**, and the system will predict whether they have diabetic retinopathy and identify its **stage**.  

---

## 🧠 Project Overview

- The system uses a **pre-trained convolutional neural network (CNN)** model trained on retinal fundus images.  
- The **Flask backend** handles image uploads, processes them through the model, and returns predictions.  
- The **React Native mobile app** provides a user-friendly interface for uploading images and viewing prediction results in real time.  

---

## ⚙️ Tech Stack

**Frontend (Mobile App):** React Native  
**Backend (Server):** Flask (Python)  
**AI Model:** Pre-trained CNN model for Diabetic Retinopathy detection  
**Libraries Used:**  
- TensorFlow / Keras  
- NumPy, OpenCV, Pillow  
- Flask, Flask-CORS  
- Axios (for frontend-backend connection)  

---

## 🚀 Features

- 📷 Upload retina image from gallery or camera  
- 🤖 AI-based prediction for diabetic retinopathy  
- 🩸 Shows detection result: **No DR / Mild / Moderate / Severe / Proliferative**  
- 🔁 Real-time communication between React Native app and Flask API  
- 📊 Displays confidence score for predictions  
- 🌐 Flask API easily deployable on any server  

---

## 📱 App Workflow

1. User uploads or captures an eye image from the React Native app.  
2. The image is sent to the Flask backend via an API request.  
3. The Flask backend processes the image using the pre-trained model.  
4. The model predicts the presence and stage of Diabetic Retinopathy.  
5. The result is sent back to the app and displayed to the user.  

---

## 🔗 Repositories

- **Frontend (React Native):** [Diabetic_Retinopathy_Detection_App_frontend](https://github.com/sajid384/Diabetic_Retinopathy_Detection_App_Frontend)  
- **Backend (Flask):** [Diabetic_Retinopathy_Detection_App_Backend](https://github.com/sajid384/Plant_Disease_Detection_System_Backend)  

---

## 👨‍💻 Author

**Syed Sajid Hussain**  
Full Stack & AI Developer  
