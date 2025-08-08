🛡️ IoT Network Intrusion Detection System using AI/ML

This is a minor project developed by students of SDMCET AIML Department to detect malicious activity in IoT networks using advanced AI and ML techniques.

---

 📚 Project Summary

- **Title:** IoT Network Intrusion Detection System (IDS) using AI/ML
- **Model Used:** CNN + LSTM (Deep Learning)
- **Domain:** Cybersecurity, Industrial IoT
- **Dataset:** KDD Cup 1999 / Simulated IoT data
- **Frameworks:** Python, TensorFlow/Keras, Flask
- **Team:** Sudev Basti and team (2SD22AI060)

---

 🚀 Features

- Real-time intrusion detection via a trained deep learning model.
- Frontend interface (HTML/JS) to input network data and get predictions.
- Trained `.h5` model file integrated with Flask backend.
- Supports multi-class classification (Normal, DoS, U2R, R2L).




---

💻 Technologies Used

- **Flask** – for web API
- **TensorFlow/Keras** – for CNN + LSTM model
- **HTML/JavaScript** – for frontend input form
- **Postman** – for testing API routes

---

🧠 Model Architecture

- **CNN**: Used for spatial feature extraction from traffic data
- **LSTM**: Used for learning temporal sequence patterns
- **MinMaxScaler & LabelEncoder** used for preprocessing



🛠️ How to Run Locally

```bash
git clone https://github.com/your-username/NIDS-AI-ML-Project.git
cd NIDS-AI-ML-Project
pip install -r requirements.txt
python app.py


