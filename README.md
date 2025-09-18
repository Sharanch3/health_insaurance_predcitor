# 🏥 Health Insurance Premium Prediction

An interactive **machine learning web app** that predicts **health insurance premium amounts** based on user input and medical history.

---

## 🌟 Features
- 💡 **Age-based prediction**: Separate ML models for **young** and **rest** age groups  
- ⚡ **Pre-trained models & scalers** for fast and accurate predictions  
- 🧩 Handles **both categorical and numerical features**  
- 📊 **Normalizes medical risk scores** for better model performance  

---

## 🚀 Live Demo
👉 [**Click here to try the app**](https://health-insaurance-predcitor.streamlit.app/)  

---

## 📁 Project Structure
```
├── app.py                  # Streamlit app entry point
├── prediction_helper.py     # Core prediction logic
├── artifacts/              # Trained models and scalers
│   ├── model_rest.joblib
│   ├── model_young.joblib
│   ├── scaler_rest.joblib
│   └── scaler_young.joblib
├── data/                   # Sample data
│   └── premiums_*.xlsx
├── notebooks/              # Jupyter notebooks for EDA & model training
│   └── *.ipynb
├── requirements.txt        # Python dependencies
├── pyproject.toml
└── README.md
```

---

## 🛠️ Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/health-insurance-prediction.git
cd health-insurance-prediction
```
*(Replace `yourusername` with your GitHub username)*

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the app locally
```bash
streamlit run app.py
```

---

## 💻 Usage
- Enter **user details** and **medical history** in the app interface.  
- The app will predict the insurance premium using the appropriate model.

---

## 🧠 Model Details
- Pre-trained **models and scalers** are stored in the `artifacts/` directory.  
- The prediction logic is implemented in [`prediction_helper.py`](prediction_helper.py).

---

## 📜 License
This project is licensed under the **MIT License** – feel free to use and modify.

---

## 📬 Contact
For questions or feedback:  
- Open an **issue** in this repository, or  
- Reach out via GitHub: (https://github.com/Sharanch3)  

---


