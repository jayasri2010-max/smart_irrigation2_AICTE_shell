# smart_irrigation2_AICTE_shell
Smart Irrigation System 💧🤖

An AI-based irrigation system that predicts whether the sprinkler should be ON or OFF using sensor values like soil moisture, temperature, and humidity. The model is trained with data and deployed using Python and Streamlit for an easy-to-use interface.

✨ Features

AI/ML model to predict sprinkler status.

Inputs: Soil Moisture, Temperature, Humidity.

Interactive web app using Streamlit.

Can be extended with more sensors or real hardware.

🧠 How it Works

Collect and preprocess dataset (sensor readings).

Train a Machine Learning model (e.g., Random Forest).

Save trained model with joblib.

Streamlit app takes user input and predicts Sprinkler ON/OFF.

🚀 Getting Started
Install dependencies:
pip install -r requirements.txt

Train the model:
python train_model.py

Run the app:
streamlit run app.py

📌 Future Improvements

Add weather API for smarter predictions.

Connect to IoT devices (ESP32/Arduino + pump).

Add logs, charts, and analytics of irrigation history.

🪪 License

This project is open-source. You can use and modify it freely.

