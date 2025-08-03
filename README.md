# 🌱 Smart Irrigation System using Soil Moisture & Weather Data  

## 📌 Overview  
This project demonstrates an **AI-powered Smart Irrigation System** that predicts **sprinkler activation (ON/OFF)** for multiple farm parcels based on **soil moisture sensor readings** and **weather data**.  

The system uses **Machine Learning** for intelligent decision-making and provides a **Streamlit web application** for farmers to easily input sensor values and visualize irrigation recommendations in real time.

---

## 🎯 Objectives  
- ✅ **Optimize water usage** in agriculture through AI.  
- ✅ Integrate **soil moisture** and **weather conditions** to predict irrigation needs.  
- ✅ Build an **interactive dashboard** for farmers and stakeholders.  
- ✅ Contribute to **sustainable and resource-efficient farming practices**.

---

## 🛠 Tools & Technologies Used  
### 🔹 Programming & Development  
- **Python** – Core language for ML model & deployment  
- **Jupyter Notebook** – Data preprocessing & model training  

### 🔹 Machine Learning & Data Handling  
- **Scikit-learn** – Algorithm implementation  
- **Pandas, NumPy** – Data manipulation & computation  
- **Joblib** – Saving/loading trained ML model  

### 🔹 Deployment & Interface  
- **Streamlit** – Web-based dashboard for predictions  

### 🔹 Visualization  
- **Matplotlib / Seaborn** – Data visualization (in notebook)  

### 🔹 Sensors & Data Inputs  
- **Soil Moisture Sensors** – Primary input for irrigation prediction  
- **Weather Data Sources** – Temperature, humidity & rainfall data

---

## 🔬 Methodology  

1️⃣ **Problem Definition & Goal** – Identified the need for AI-driven irrigation optimization.  
2️⃣ **Data Collection & Preprocessing** – Soil moisture & weather data gathered, cleaned, and scaled (0–1).  
3️⃣ **Model Training** – Tested algorithms (e.g., Decision Trees, Random Forest) & saved final model as `Farm_Irrigation_System.pkl`.  
4️⃣ **Model Evaluation** – Tuned model for improved accuracy.  
5️⃣ **App Development** – Streamlit app built with sliders for 20 sensor inputs.  
6️⃣ **Deployment & Future Scope** – Ready for IoT integration for fully automated irrigation.

---

## 📂 Project Structure  

📦 Smart-Irrigation-System

┣ 📜 app1.py # Streamlit web application

┣ 📜 week2.ipynb # Model training & preprocessing notebook

┣ 📜 Farm_Irrigation_System.pkl # Trained ML model

┣ 📜 README.md # Project documentation

┗ 📂 screenshots # Output screenshots



---

## 🚀 How to Run the Project  

### 🔧 **Step 1: Clone the Repository**

git clone https://github.com/your-username/smart-irrigation.git

cd smart-irrigation

🔧 Step 2: Install Dependencies

pip install -r requirements.txt

🔧 Step 3: Run the Streamlit App

streamlit run app1.py

🔧 Step 4: Use the Dashboard

Adjust 20 soil moisture sensor sliders (values between 0–1).

Click Predict Sprinklers.

View ON/OFF sprinkler recommendations for each farm parcel.



🌟 Features

✅ Parcel-wise irrigation predictions (ON/OFF).

✅ Interactive UI with sliders for real-time sensor values.

✅ AI-driven water management for sustainable agriculture.

✅ Future scope for IoT & fully automated irrigation.

Output Screenshots:
<img width="1257" height="580" alt="image" src="https://github.com/user-attachments/assets/31873d20-d5f1-49a0-a12d-94cbd92b37ff" />
<img width="1277" height="536" alt="image" src="https://github.com/user-attachments/assets/7fcded58-f401-4e96-9695-1b69678d9eaa" />



📈 Future Enhancements

🌐 IoT device integration for automatic sprinkler control.

🌦 Live weather API for dynamic predictions.

📱 Mobile app version for easier farmer access.

👩‍💻 Author

Shalini I.

B.Tech Computer Science | Crescent University

📜 License

This project is licensed under the MIT License – see the LICENSE file for details.
