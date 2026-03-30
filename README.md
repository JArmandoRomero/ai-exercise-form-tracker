# 🧠 AI Exercise Form Correction & Nutrition Tracking System

## 📌 Overview
This project is a full-stack deep learning-powered fitness system designed to analyze human exercise form in real time using computer vision and machine learning.

The system detects body posture, evaluates movement quality, and provides corrective feedback while also tracking workouts and nutrition.

---

## 🚀 Key Features
- Real-time pose detection using MediaPipe  
- Deep learning-based form classification (MLP / LSTM)  
- Live feedback on exercise technique  
- Workout and nutrition tracking  
- REST API with OpenAPI (Swagger)  
- Modular microservice architecture  

---

## 🏗️ System Architecture
Frontend → .NET API → DL Service → Pose Detection → Camera

---

## 🧩 Tech Stack

### Backend
- ASP.NET Core (.NET 6/7/8)
- OpenAPI / Swagger

### Machine Learning
- Python
- FastAPI
- TensorFlow / PyTorch
- Scikit-learn

### Computer Vision
- MediaPipe

### Frontend
- React (optional)

### Database
- SQL Server / SQLite

---

## 📁 Project Structure

ai-exercise-form-tracker/
│
├── backend-dotnet/
│   ├── AiExerciseFormTracker.sln
│   ├── src/
│   │   └── Api/
│   ├── tests/
│
├── ml-service/
│   ├── model/
│   ├── preprocessing/
│   ├── api/
│
├── frontend/
├── data/
├── docs/
│   └── diagrams/

---

## 🔄 Data Flow

Camera → Pose Detection → Feature Extraction → ML Model → Feedback → UI

Frontend → .NET API → ML Service → Response → UI

---

## 📊 System Design

- Architecture Diagram
- Sequence Diagram
- Class Diagram
- ML Model Diagram

---

## 🤖 Deep Learning Pipeline

1. Capture video input  
2. Extract pose landmarks  
3. Compute joint angles  
4. Build temporal sequences  
5. Train model  

---

## ⚙️ Setup Instructions

### Backend (.NET)
cd backend-dotnet/src/Api  
dotnet run  

### ML Service (Python)
cd ml-service  
python -m venv venv  
activate venv  

pip install fastapi uvicorn mediapipe opencv-python numpy scikit-learn  
uvicorn api.main:app --reload  

---

## 🧪 Testing
- Swagger API testing  
- Model evaluation  
- Integration testing  

---

## 📊 Evaluation Metrics
- Accuracy  
- Precision / Recall  
- F1 Score  
- Latency  

---

## 🔮 Future Improvements
- Mobile app  
- Advanced ML models  
- Multi-exercise support  

---

## 👤 Author
Jarrod Romero- University of Tennessee Knoxville
