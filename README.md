# 🌾 Crop Prediction using Machine Learning

A machine learning web application that helps farmers make informed decisions about crop selection based on soil and weather conditions.

---

## 📌 Overview

This project uses a trained machine learning model to predict the most suitable crop to grow based on environmental and soil parameters. Farmers can input a few key values and instantly receive a recommendation, reducing guesswork and improving agricultural efficiency.

---

## 🚀 Features

- Predicts the best crop based on soil nutrients and weather data
- Simple and intuitive web interface built with Streamlit
- Trained on a balanced dataset of 2200 samples across 22 crop types
- High accuracy, outperforming traditional crop prediction methods

---

## 🗂️ Project Structure

```
crop-app/
├── app.py               # Streamlit web application
├── model code.txt       # Model training code
├── model.pkl            # Trained ML model (pickle file)
├── prerequisites        # Prerequisites and setup notes
├── requirements.txt     # Python dependencies
└── README.md
```

---

## 📊 Dataset

The model was trained on the [Crop Prediction Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset), which consists of:

- **2200 samples** across **22 different crops**
- **7 input features:**
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - pH value of the soil
  - Temperature (°C)
  - Humidity (%)
  - Rainfall (mm)

The dataset is perfectly balanced with 100 samples per crop.

---

## 🧠 Model

The model was trained using machine learning classification techniques. The trained model is saved as `model.pkl` and loaded directly in the app for real-time predictions.

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/ayushthakur874485-arch/crop-app.git
cd crop-app
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the app

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

---

## 🖥️ Usage

1. Open the app in your browser
2. Enter the soil and weather values:
   - Nitrogen, Phosphorus, Potassium levels
   - Soil pH, Temperature, Humidity, Rainfall
3. Click **Predict**
4. The app will display the recommended crop

---

## 📦 Requirements

See `requirements.txt` for the full list. Key dependencies include:

- Python 3.x
- scikit-learn
- pandas
- numpy
- streamlit

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**ayushthakur874485-arch**  
GitHub: [@ayushthakur874485-arch](https://github.com/ayushthakur874485-arch)
