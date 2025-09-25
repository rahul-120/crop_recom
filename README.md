---
title: Crop Recomd
emoji: 🏆
colorFrom: green
colorTo: gray
sdk: docker
pinned: false
short_description: This is my first ml project
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

---

# 🌱 Crop Recommendation System  

This project is a **Machine Learning based Crop Recommendation System** built using **Flask**.  
It helps farmers or users decide the most suitable crop to grow based on soil nutrients and environmental conditions.  

🔗 **Live Demo**: [Crop Recommendation App](http://mahesh2045-crop-recomd.hf.space/)  

---

<img width="424" height="339" alt="image" src="https://github.com/user-attachments/assets/cb7b19bf-ce71-496f-96b7-32ffcbc8e51c" />


## 🚀 Features
- Predicts the best crop based on input values:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature
  - Humidity
  - pH
  - Rainfall
- Simple and interactive **web interface** built with Flask.
- Model trained on agricultural datasets.
- Hosted online using **Hugging Face Spaces**.

---

## 🛠️ Tech Stack
- **Python**
- **Flask** (Web Framework)
- **NumPy** (Data Handling)
- **Pickle** (Model Serialization)
- **HTML/CSS** (Frontend)

---

## 📂 Project Structure
```

├── app.py              # Main Flask application
├── model.pkl           # Trained ML model
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
* It uses classification techniques to map environmental features to a set of possible crops.

---

## 🌍 Deployment

* Hosted using **Hugging Face Spaces**:
  [http://mahesh2045-crop-recomd.hf.space/](http://mahesh2045-crop-recomd.hf.space/)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the **MIT License**.

---

### 👨‍💻 Author

* **Rahul Bhaskar**
  🔗 [GitHub Profile](https://github.com/rahul-120)
Would you also like me to create a **requirements.txt (without versions)** for this project so that it’s easier for others to run locally?
```
