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
