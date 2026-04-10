# EchoSafe – AI-Based Real-Time Distress Sound Detection System

EchoSafe is an AI-driven audio surveillance system designed to detect distress sounds such as screams, alarms, sirens, and violent impact noises in real time. The system focuses on enhancing public safety while maintaining user privacy through on-device processing.

---

## 🚀 Features

- Real-time distress sound detection
- MFCC-based audio feature extraction
- Hybrid ML model (CNN-Transformer + MLP-SVM)
- FastAPI-based backend
- Web interface for interaction
- Secure alert triggering mechanism
- Privacy-focused (no continuous audio storage)

---

## 🧠 Tech Stack

- Python
- TensorFlow / Keras
- Scikit-learn
- Librosa
- FastAPI
- HTML / CSS / JavaScript
- Docker

---

## ⚙️ Project Structure


EchoSafe/
│
├── config/
├── model/
├── static/
├── templates/
├── uploaded_audio/
├── testing_chunks/
│
├── main.py
├── utils.py
├── gunshot_detector.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml


---

## 🔍 How It Works

1. Audio input is captured or uploaded  
2. Preprocessing is applied (noise reduction, segmentation)  
3. MFCC features are extracted  
4. Features are passed to trained ML model  
5. Model classifies audio as distress / non-distress  
6. Alert is triggered if distress is detected  

---

## ▶️ How to Run

### Step 1: Install dependencies

pip install -r requirements.txt


### Step 2: Run the application

python main.py


---

## 📊 Applications

- Smart city surveillance  
- Public transport safety  
- Campus security  
- Elderly monitoring  
- Personal safety systems  

---

## ⚠️ Limitations

- Performance depends on audio quality  
- Background noise can affect accuracy  
- Requires trained model for best results  

---

## 👨‍💻 Authors

- Prakhar Dhimaan  
- Siddharth Singh  
- Neelabh Srivastava  
- Sahil Kumar Jha  

---

## 📌 Note

This project is developed as a Final Year B.Tech Project (CSE - AI & ML) at KIET Group of Institutions.
