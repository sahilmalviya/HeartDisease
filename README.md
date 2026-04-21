# ❤️ Heart Stroke Prediction

This project is a Machine Learning-based web application built using Streamlit that predicts the likelihood of a heart stroke using patient health data.

## 🚀 Project Overview
The goal of this project is to help in early detection of stroke risk by analyzing various medical parameters. The model uses the K-Nearest Neighbors (KNN) algorithm for prediction.

## 🛠️ Tech Stack
- Python  
- Streamlit  
- Scikit-learn  
- Pandas  
- NumPy  

## 📂 Project Structure
```
├── app.py                 # Streamlit web application
├── knn_heart_model.pkl    # Trained KNN model
├── scaler.pkl             # Data scaler for preprocessing
├── columns.pkl            # Feature columns used in model
├── requirements.txt       # Required dependencies
```

## ⚙️ How It Works
1. User inputs health-related data via Streamlit UI  
2. Data is preprocessed using a scaler  
3. The trained KNN model predicts stroke risk  
4. Result is displayed instantly on the web app  

## 💻 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/sahilmalviya/HeartDisease.git
cd HeartDisease
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the app
```bash
streamlit run app.py
```

## ✨ Features
- Interactive UI using Streamlit  
- Real-time prediction  
- Lightweight and easy to use  
- Clean and simple design  

## 📊 Future Improvements
- Improve model accuracy  
- Add more medical parameters  
- Deploy on Streamlit Cloud  
- Better UI/UX enhancements  

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

⭐ If you found this project useful, give it a star!
