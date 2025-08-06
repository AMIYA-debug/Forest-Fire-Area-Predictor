# 🔥 Algerian Forest Fire Area Prediction

This project predicts the area affected by forest fires in Algeria using meteorological and environmental data. By analyzing various input features such as temperature, humidity, wind speed, fire indices, and more, the model estimates the area likely to be burned in hectares. This tool aims to assist forest management teams, environmentalists, and disaster response units in preparing for and mitigating wildfire damage.

---

## 📌 Project Overview

Wildfires in Algeria, particularly in the northeast regions, pose a serious threat to biodiversity, the environment, and nearby populations. This machine learning model is trained on a dataset containing fire events with features including:

- **Date features**: Day, Month, Year  
- **Weather conditions**: Temperature, Relative Humidity (RH), Wind Speed (Ws), Rain  
- **Fire indices**: FFMC, DMC, DC, ISI, BUI, FWI  
- **Metadata**: Region, Class (fire/no fire)

The model provides predictions for the **area affected by forest fires** in hectares, helping stakeholders plan fire suppression and disaster response strategies effectively.

---

## 🧠 Model Details

- **Algorithm**: Multiple Linear Regression  
- **Dataset**: Algerian Forest Fires Dataset  
- **Features used for training**:
  - `Day`, `Month`, `Year`
  - `Temperature`, `Relative Humidity (RH)`, `Wind Speed (Ws)`, `Rain`
  - `FFMC`, `DMC`, `DC`, `ISI`, `BUI`, `FWI`
  - `Classes`, `Region`
- **Target variable**: `Area` (in hectares)

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/AMIYA-debug/Algerian-Forest-Fire-Predictor.git
cd Algerian-Forest-Fire-Predictor
```

I used Flask as the backend framework along with HTML and CSS to build a functional and responsive web application interface. This integration allows users to interact with the model through a clean and simple web form. The input data is passed from the webpage to the Flask backend, where the trained machine learning model processes it and returns the predicted forest fire risk. This setup provides an end-to-end solution from model training to real-time prediction on a user-friendly web platform.

---

## 📂 Project Structure

```bash
ALGERIAN_FIRE_PREDICTION/
│
├── dataset/
│   ├── Algerian_forest_fires_dataset.csv
│   └── [Processed/cleaned datasets]
│
├── models/
│   ├── ridge.pkl        # Trained Ridge Regression model
│   └── scaler.pkl       # Standard Scaler used in preprocessing
│
├── notebook/
│   ├── 2.0-EDA And FE.ipynb      # Exploratory Data Analysis + Feature Engineering
│   └── modeltrain.ipynb          # Model training + evaluation
│
├── templates/
│   ├── home.html        # UI for model input
│   └── index.html       # Landing page with model info
│
├── application.py       # Main Flask app
├── requirements.txt     # Python dependencies
└── README.md            # You are here 📘
```





