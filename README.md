# 🛡️ Network Intrusion Detection System (NIDS)
**Master of Computer Applications (MCA) - Security-Focused ML Portfolio Project**

An end-to-end Machine Learning application built to identify network threats (DoS, Probe, R2L) using the **NSL-KDD dataset**. This project features a **Streamlit UI** and a **Hybrid Detection Logic** to enhance accuracy in stealth attack scenarios.

---

## 🚀 Key Features
- **Real-time Prediction**: Classifies traffic as "Normal" or "Malicious" instantly.
- **XGBoost Classifier**: Optimized for high-speed, high-accuracy classification.
- **Hybrid Heuristics**: Integrated custom logic to catch unauthorized data exfiltration (R2L attacks).
- **Intuitive UI**: Built with Streamlit for a professional-grade security analyst dashboard.

---

## 🧪 Detection Scenarios
The model is trained and tested to detect:
1. **Denial of Service (DoS)**: Recognizing high SYN error rates and half-open connections.
2. **Probing**: Detecting port scans and network mapping attempts.
3. **Data Exfiltration**: Identifying unauthorized large data transfers on unauthenticated sessions.

---

## 🛠️ Tech Stack
- **Language**: Python
- **Libraries**: Scikit-Learn, XGBoost, Pandas, Numpy
- **UI Framework**: Streamlit
- **Model Deployment**: Pickle for serialization

---

## 📂 Project Structure
network-intrusion-detection-system/<br/>
│── data/<br/>
│ ├── KDDTest+.txt<br/>
│ └── KDDTrain+.txt<br/>
│<br/>
│── models<br/>
│ ├── columns.pkl<br/>
│ ├── intrusion_model.pkl<br/>
│ └── scaler.pkl<br/>
│<br/>
│── notebook/.ipynb_checkpoints<br/>
│ └── network-intrusion-detection-system.ipynb<br/>
│<br/>
│── README.md<br/>
│<br/>
│── screenshots/<br/>
│ ├── DoSAttack(Malicious).png<br/>
│ ├── dataTheft(Malicious).png<br/>
│ ├── loadpage.png<br/>
│ ├── normalWeb(Safe).png<br/>
│ └── portScan(Malicious).png<br/>
│<br/>
│── app.py<br/>
└── requirements.txt<br/>

---

## 📥 Installation & Usage
~~~
1. Clone the repository:
   git clone [https://github.com/panchajanya-ray/network-intrusion-detection-system.git](https://github.com/your-username/network-intrusion-detection-system.git)

2. Install dependencies:
   pip install -r requirements.txt

3. Run the application:
   streamlit run app.py
~~~

---

## 📸 Screenshots

### Main Interface
![Main UI](screenshots/loadpage.png)

### Normal Web (Safe)
![Normal Web](screenshots/normalWeb(Safe).png)

### DoS Attack (Malicious)
![DoS Attack](screenshots/DoSAttack(Malicious).png)

### Data Theft (Malicious)
![Data Theft](screenshots/dataTheft(Malicious).png)

### Port Scan (Malicious)
![Port Scan](screenshots/portScan(Malicious).png)

---

## 👨‍💻 Author

PANCHAJANYA RAY<br/>
MCA Student | ML Engineer<br/>
https://github.com/panchajanya-ray
