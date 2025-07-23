# AiHealthAssistant (SehatSutraAI)

SehatSutraAI is an AI-based health assistant web application designed to help users assess symptoms, find medical advice, and connect with doctors. It offers a seamless experience through an intelligent chatbot, health data analytics, and optional payment features.

## 🌐 Live Demo
*Coming Soon*

---

## 🚀 Features

- 🤖 **AI Chatbot**: For health-related queries and symptom checking.
- 👨‍⚕️ **Doctor Directory**: Find and connect with medical professionals.
- 📋 **Symptom Checker**: Based on user input and `symptoms.json`.
- 🔐 **Authentication System**: Secure login/signup using JWT.
- 💳 **Payment Gateway Support** *(beta)*: Integrates a basic payment system (likely blockchain-based).
- 🖼️ Clean and responsive UI with TailwindCSS.

---

## 🛠️ Tech Stack

### Frontend:
- React
- Tailwind CSS
- Vite

### Backend:
- Node.js
- Express.js
- MongoDB (assumed from typical structure)
- JWT for Auth

### Extras:
- Blockchain module (via `Move.toml` and `payment_gateway`)
- JSON-based AI data models

---
## 📁 Project Structure

```plaintext

SehatSutraAI-master/
├── backend/ # Express backend
├── src/ # React frontend source
├── public/ # Static assets
├── build/payment_gateway # Blockchain/payment logic
├── symptoms.json # AI logic dataset
├── doctorsData.js # Doctor information
└── index.html # Entry point

