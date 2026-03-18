<!-- # Vehicle Damange Detection App

This app let's you drag and drop an image of a car and it will tell you what kind of damage it has.
The model is trained on third quarter front and rare view hence the picture should capture the third quarter front or rare view of a car. 

![app](app_screenshot.jpg)

### Model Details
1. Used ResNet50 for transfer learning
2. Model was trained on around 1700 images with 6 target classes
   1. Front Normal
   1. Front Crushed
   1. Front Breakage
   1. Rear Normal
   1. Rear Crushed
   1. Rear Breakage
9. The accuracy on the validation set was around 80%

### Set Up

1. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
2. Run the streamlit app:
   ```commandline
   streamlit run app.py
   ``` -->

   🚗 Vehicle Damage Detection using Deep Learning
📌 Overview

This project is a Deep Learning-based Vehicle Damage Detection System that identifies whether a vehicle is damaged or not from an uploaded image. It uses a trained model and a user-friendly Streamlit web app for real-time predictions.

![app](app_screenshot.jpg)

🎯 Features

📷 Upload vehicle images بسهولة (JPG, PNG, JPEG)

🤖 AI-based damage detection

⚡ Fast and real-time predictions

🖥️ Interactive UI using Streamlit

🧠 Trained deep learning model (PyTorch)

🏗️ Project Structure
Damage-Prediction/
│── dataset/                      # Training dataset
│── streamlit-app/               # Web application
│   ├── app.py
│   ├── model/
│   ├── model_helper.py
│   ├── requirements.txt
│   └── README.md
│── saved_model.pth              # Trained model
│── damage_prediction.ipynb      # Model training notebook
│── hyperparameter_tunning.ipynb # Hyperparameter tuning
│── README.md                    # Main project README
🧠 Model Details

Framework: PyTorch

Task: Binary Image Classification (Damaged / Not Damaged)

Techniques:

Image preprocessing

Model training & evaluation

Hyperparameter tuning

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/Damage-Prediction.git
cd Damage-Prediction
2️⃣ Install Dependencies
pip install -r streamlit-app/requirements.txt
3️⃣ Run the Streamlit App
cd streamlit-app
streamlit run app.py
🖼️ Demo




📊 Future Improvements

🔍 Detect type of damage (dent, scratch, crack)

📦 Deploy on cloud (AWS / Render / HuggingFace)

📱 Mobile-friendly UI

🎯 Improve model accuracy

🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

📧 Contact

Rahul Bora
📍 Assam, India
💼 Aspiring ML Engineer

⭐ If you like this project, give it a star!