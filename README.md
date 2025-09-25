---
title: Crop Recomd
emoji: 🌱
colorFrom: green
colorTo: gray
sdk: docker
pinned: false
short_description: Machine Learning based Crop Recommendation System built using Flask
---

# 🌱 Crop Recommendation System  

[![Made with Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)  
[![Flask](https://img.shields.io/badge/Flask-Web%20Framework-lightgrey?logo=flask)](https://flask.palletsprojects.com/)  
[![scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)](https://scikit-learn.org/)  
[![Deploy on Hugging Face](https://img.shields.io/badge/Deploy-HuggingFace-yellow?logo=huggingface)](http://mahesh2045-crop-recomd.hf.space/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

This project is a **Machine Learning based Crop Recommendation System** built using **Flask**.  
It helps farmers or users decide the most suitable crop to grow based on soil nutrients and environmental conditions.  

🔗 **Live Demo**: [Crop Recommendation App](http://mahesh2045-crop-recomd.hf.space/)  

---

## 📸 Screenshot  

<img width="424" height="339" alt="Crop Recommendation Demo" src="https://github.com/user-attachments/assets/cb7b19bf-ce71-496f-96b7-32ffcbc8e51c" />

---

## 🚀 Features
- Predicts the best crop based on input values:
  - 🌾 Nitrogen (N)  
  - 🌿 Phosphorus (P)  
  - 🌱 Potassium (K)  
  - 🌡️ Temperature  
  - 💧 Humidity  
  - ⚗️ pH  
  - ☔ Rainfall  
- Simple and interactive **web interface** built with Flask.  
- Model trained on agricultural datasets.  
- Hosted online using **Hugging Face Spaces**.  

---

## 🛠️ Tech Stack
- **Python**  
- **Flask** (Web Framework)  
- **NumPy** (Data Handling)  
- **Pickle** (Model Serialization)  
- **scikit-learn** (Machine Learning)  
- **HTML/CSS** (Frontend)  
- **Gunicorn** (Deployment on Hugging Face)  

---

## 📂 Project Structure
```

├── app.py              # Main Flask application
├── model.pkl           # Trained ML model
├── requirements.txt    # Dependencies
├── templates
│   └── index.html      # Frontend HTML file
├── static/             # (Optional) For CSS/JS files
└── README.md           # Project Documentation

````

---

## ⚙️ Installation & Usage  

### 1. Clone the repository  
```bash
git clone https://github.com/rahul-120/crop_recom.git
cd crop_recom
````

### 2. Create and activate a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Flask app

```bash
python app.py
```

### 5. Open in browser

Go to `http://127.0.0.1:5000/`

---

## 🧠 Model Details

* The model is trained to recommend the most suitable crop based on soil and weather conditions.
* It uses classification techniques from **scikit-learn** to map environmental features to a set of possible crops.

---

## 🌍 Deployment

* Hosted using **Hugging Face Spaces (Docker SDK)**
* Live App: [http://mahesh2045-crop-recomd.hf.space/](http://mahesh2045-crop-recomd.hf.space/)

---

## 📦 Requirements

`requirements.txt` (no versions for flexibility):

```
flask
gunicorn
scikit-learn
joblib
numpy
```

---

## 🤝 Contributing

Contributions are welcome! 🎉

1. Fork the repo
2. Create a new branch (`feature-xyz`)
3. Commit changes
4. Push to your branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

### 👨‍💻 Author

**Rahul Bhaskar**
🔗 [GitHub Profile](https://github.com/rahul-120)
