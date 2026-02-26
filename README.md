🌾 BhoomiAI
AI-Powered Smart Agriculture Platform
BhoomiAI is an intelligent agriculture decision-support platform built using AI, machine learning, and multilingual conversational assistance. It helps farmers and users make informed crop decisions through disease detection, AI advisory, and digital twin simulation technology.

🚀 Live Deployment
🌐 Frontend (User Interface)
👉 https://bhoomi-frontend.onrender.com

🔗 Backend API
👉 https://bhoomi-backend-7hlj.onrender.com

🎯 Core Features
🤖 AI Agriculture Expert (Powered by Ollama)
Intelligent farming advisory system
AI-generated agricultural recommendations
Context-aware soil and crop analysis
Multilingual support (English, Hindi, Telugu)
Uses locally hosted Ollama model for AI generation (in development mode)

🛰 Digital Twin Simulation
Simulated decision preview
Allows users to explore crop scenarios
Smart planning support before real implementation

🌱 Crop Disease Detection
Image-based tomato leaf disease detection
Supports detection of:
Tomato Target Spot
Tomato Mosaic Virus
Tomato Yellow Leaf Curl Virus
Healthy leaf classification
Confidence score output
Smart recommendation rotation system
Simulation fallback mode if ML model is unavailable

🛠️ Technology Stack
🖥 Frontend

React (Vite)
Tailwind CSS
JavaScript (ES6+)
Responsive Design

⚙ Backend
Python
Flask
Flask-CORS
Gunicorn (Production Server)
Deep Translator (Multilingual support)
Ollama (AI model for advisory logic)
TensorFlow / Keras (ML model loading)
NumPy
Scikit-Learn

☁ Deployment
Render (Static Site – Frontend)
Render (Web Service – Backend)

🔥 Ollama Integration
In local development:
Ollama is used for AI text generation
Model: llama3.2:1b
Generates smart agricultural advisory responses
In production deployment (Render):
Ollama is conditionally disabled
Application remains stable without crashing
Clean fallback messages are returned
This ensures production-safe deployment while maintaining AI functionality in development.

