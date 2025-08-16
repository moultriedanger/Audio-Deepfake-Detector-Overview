<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h1 align="center">Audio Deepfake Detection – Overview</h1>
  <p align="center">
    A Flask-based web application that uses a PyTorch-trained model to detect synthetic (AI-generated) speech.
    <br />
    Built to help identify deepfake audio in real time, with an intuitive upload interface and clear prediction results.
    <br />
    <a href="https://audio-deepfake-detector.vercel.app/"><strong>Live Demo »</strong></a>
    <br />
    <br />
    <a href="https://github.com/moultriedanger/audio-deepfake-detector-frontend">Frontend Repo</a>
    &middot;
    <a href="https://github.com/moultriedanger/audio-deepfake-detector-api">Backend Repo</a>
  </p>
</div>

---

## 📂 Project Repositories

- **Frontend (React + JSX)** → [Audio Deepfake UI](https://github.com/moultriedanger/audio-deepfake-detector-frontend)  
  Responsive React interface for uploading audio, displaying inference results, and guiding users through the detection process.

- **Backend (Flask + PyTorch)** → [Audio Deepfake API](https://github.com/moultriedanger/audio-deepfake-detector-api)  
  Flask REST API that loads the pretrained deepfake detection model and performs inference on uploaded audio files.

---

## 🔹 Features

### Frontend
- React for modern ui
- Drag-and-drop or file picker for audio uploads
- Real-time progress indicator during model inference
- Clear pass/fail probability output

### Backend
- Flask RESTful API
- PyTorch-based synthetic voice detection model
- Pretrained checkpoint (`librifake_pretrained_lambda0.5_epoch_25.pth`)
- S3 model storage with on-demand download
- File cleanup after inference to save server resources

---

## 📌 Tech Stack

**Frontend**: React, JavaScript, JSX, Tailwind CSS  
**Backend**: Python, Flask, PyTorch, boto3, NumPy  
**Deployment**: Vercel (Frontend), AWS EC2 / Gunicorn (Backend)  

---

## 📧 Contact

Moultrie Dangerfield – moultriedanger@gmail.com  
[LinkedIn](https://www.linkedin.com/in/moultriedangerfield) | [GitHub](https://github.com/moultriedanger)
