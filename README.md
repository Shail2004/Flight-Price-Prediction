# ✈️ Flight Price Prediction

A **Flight Price Prediction** application that allows users to input flight details through a React-based frontend form. The data is processed by a Flask backend, which utilizes a trained machine learning model to predict flight ticket prices.

---

## 🖥️ Project Overview

This project is designed to provide a seamless experience for users to predict flight ticket prices based on key input parameters such as the source, destination, date of travel, and other flight-related details.  

### Tech Stack:
- **Frontend**: React  
- **Backend**: Flask  
- **Machine Learning Model**: Trained using Python libraries and stored as a `.pkl` file.  

---

## 📂 Directory Structure

```
📦 Flight Price Prediction
├── flight-prediction/      # Frontend folder (React)
├── app.py                  # Flask backend entry point
├── Flight Price Prediction Using Python.ipynb  # Jupyter notebook for exploration and training
├── flight.xlsx             # Dataset used for training the ML model
├── model.pkl               # Serialized machine learning model
└── .gitignore              # Git ignore file
```

---

## 🚀 Features
1. **Frontend (React)**:
   - A user-friendly form for inputting flight details.
   - Real-time validation of inputs for user convenience.

2. **Backend (Flask)**:
   - Handles API requests from the frontend.
   - Loads the trained ML model and returns price predictions.

3. **Machine Learning**:
   - Model trained on a comprehensive flight dataset.
   - Predicts ticket prices based on parameters such as:
     - Date of Journey
     - Source and Destination
     - Airline
     - Departure and Arrival Time
     - Total Stops
     - Class

---

## 🛠️ Installation and Setup

### Prerequisites
- **Node.js** (for React frontend)
- **Python 3.8+** (for Flask backend and ML model)

### Step 1: Clone the Repository
```bash
git clone https://github.com/Shail2004/Flight-Price_prediction.git
cd flight-price-prediction
```

---

### Step 2: Set Up the Frontend (React)
```bash
cd flight-prediction
npm install       # Install dependencies
npm start         # Start the development server
```
The React app will be available at `http://localhost:5173`.

---

### Step 3: Set Up the Backend (Flask)
Start the Flask server:
   ```bash
   python app.py
   ```
The Flask app will run at (`http://127.0.0.1:5000`).

---

### Step 4: Connect Frontend and Backend
- Ensure the Flask backend URL is set in the React frontend (e.g., in `axios` or `fetch` calls).

---

## 🔮 How to Use
1. Open the React application in your browser (`http://localhost:5173`).
2. Fill out the flight details form.
3. Click on the **Predict** button to send data to the Flask backend.
4. The predicted flight price will be displayed on the screen.

---

## 🧪 Machine Learning Workflow
1. **Dataset**: The model is trained on flight pricing data (`flight.xlsx`).
2. **Preprocessing**:
   - Feature engineering and handling missing values.
   - Encoding categorical variables (e.g., airlines, routes).
3. **Model**: Trained using algorithms like Random Forest or Gradient Boosting.
4. **Output**: The model predicts flight ticket prices based on user inputs.

---

## 📝 Future Enhancements
- Add more input parameters for better prediction accuracy.
- Implement user authentication and history of predictions.
- Enhance the UI with additional features and styling.

---

## 📜 License
This project is open-source and available under the **MIT License**.

---

## 👤 Author
- **[Shail Jain](https://github.com/Shail2004)**  
Let me know if you have any suggestions for improvements!
