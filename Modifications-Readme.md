# 🤖 Gesture Control Game – Frontend (Modified)

This is the **modified frontend** for the ML-powered Gesture Control Game. It uses a webcam to recognize hand gestures (via a backend model) and allows users to play a maze-style game using only hand movements.

## ✨ What's New (Modifications)

This forked and updated version includes the following modifications:

- 🔧 Integrated with a custom Machine Learning model API (instead of random prediction).
- 🧠 Updated `api-call.js` to send real-time webcam data to the deployed ML model and receive gesture labels.
- 📦 Containerized using Docker for consistent deployment.
- ☸️ Deployed to Kubernetes using a Deployment and NodePort Service for access.
- 🧪 Tested locally via Docker at `http://localhost:8080` and in Kubernetes at `http://localhost:30080`.

---


