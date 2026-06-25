# Plant_Disease_Model
# 🌿 AI Plant Disease Detection

An AI-powered web application that detects plant diseases from leaf images using a deep learning model. The application helps farmers, researchers, and agriculture enthusiasts identify plant diseases quickly and provides disease descriptions, treatment recommendations, and prevention tips.

---

## 🚀 Features

- 🌱 Detects multiple plant diseases from leaf images
- 🤖 Deep Learning-based image classification
- 📸 Upload plant leaf images
- 📋 Disease description
- 💊 Treatment recommendations
- 🛡️ Prevention methods
- ⚡ Fast and accurate predictions
- 🎨 Interactive Streamlit interface

---

## 🛠️ Tech Stack

- Python 3.11
- TensorFlow / Keras
- Streamlit
- NumPy
- Pillow (PIL)
- OpenCV (optional)

---

## 📂 Project Structure

```
AI-Plant-Disease-Detection/
│
├── app.py                 # Streamlit application
├── disease_info.py        # Disease descriptions and treatments
├── model/
│   └── plant_model.keras  # Trained CNN model
├── images/
│   └── demo.png
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/SharvatoshPandey21/Plant_Disease_Model.git

cd Plant_Disease_Model
```

---

### 2️⃣ Create Virtual Environment

Windows

```bash
python -m venv venv
```

Activate

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open your browser and visit:

```
http://localhost:8501
```

---

## 📸 How to Use

1. Launch the application.
2. Upload a plant leaf image.
3. Click **Predict** (if applicable).
4. View:
   - Disease Name
   - Disease Description
   - Treatment
   - Prevention Tips

---

## 🌱 Supported Plant Diseases

### 🍅 Tomato

- Bacterial Spot
- Early Blight
- Late Blight
- Leaf Mold
- Septoria Leaf Spot
- Spider Mites
- Target Spot
- Yellow Leaf Curl Virus
- Mosaic Virus
- Healthy

### 🫑 Pepper Bell

- Bacterial Spot
- Healthy

### 🥔 Potato

- Early Blight
- Late Blight
- Healthy

*(Update this list according to your trained model.)*

---

## 🧠 Model Information

- Model Type: Convolutional Neural Network (CNN)
- Framework: TensorFlow / Keras
- Input: Plant Leaf Image
- Output: Disease Class Prediction

---

## 📷 Demo

Add screenshots of your application here.

Example:

```
images/demo.png
```

---

## 📋 Requirements

- Python 3.11+
- TensorFlow
- Streamlit
- NumPy
- Pillow

---

## 🔮 Future Improvements

- Support more crop species
- Confidence score visualization
- Real-time camera detection
- Disease severity estimation
- Fertilizer recommendations
- Multi-language support
- Mobile application
- Cloud deployment
- Explainable AI (Grad-CAM)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sharvatosh Pandey**

B.Tech Computer Science & Engineering  
Shri Ramswaroop Memorial College of Engineering & Management, Lucknow

GitHub:  
https://github.com/SharvatoshPandey21

---

## ⭐ Support

If you found this project helpful:

⭐ Star this repository

🍴 Fork the repository

🐛 Report issues

💡 Suggest improvements

Happy Coding! 🚀🌿
