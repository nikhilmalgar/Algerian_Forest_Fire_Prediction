# 🔥 FWI Prediction Web App

A **Flask-based Machine Learning Web Application** that predicts the **Fire Weather Index (FWI)** using a **Ridge Regression model**.  
This project showcases how to integrate an ML model with an interactive and beautifully designed web frontend for real-time predictions.

---

## 🚀 Features

- 🎯 Predicts Fire Weather Index (FWI) using Ridge Regression
- 🧠 Uses **StandardScaler** for feature normalization
- 💻 Built with **Flask** and **Scikit-learn**
- 🌈 Interactive and modern **animated frontend**
- 📊 Clean, responsive, and professional UI design

---

## 🧠 Tech Stack

| Component               | Technology                                           |
| ----------------------- | ---------------------------------------------------- |
| **Frontend**            | HTML5, CSS3, JavaScript                              |
| **Backend**             | Flask (Python)                                       |
| **Machine Learning**    | Scikit-learn (Ridge Regression, StandardScaler)      |
| **Model Serialization** | Pickle                                               |
| **Deployment**          | Flask Server / Render / Hugging Face Spaces / Heroku |

---

## 📂 Project Structure

```
├── model/
│   ├── ridge.pkl
│   ├── scaler.pkl
│
├── templates/
│   ├── index.html
│   ├── home.html
│
├── notebooks/
│   ├── 2.0-EDA And FE Algerian Forest Fires.ipynb
│   ├── 3.0-Model Training.ipynb
│
├── application.py
├── requirements.txt
├── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/fwi-prediction-app.git
cd fwi-prediction-app
```

### 2. Create and Activate Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate      # On Windows
source venv/bin/activate   # On Mac/Linux
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Flask App

```bash
python application.py
```

Then open your browser and go to 👉 **http://127.0.0.1:5000/**

---

## 🧩 How It Works

1. User enters **Temperature, RH, Wind Speed, Rain**, and other parameters.
2. The data is scaled using **StandardScaler**.
3. The **Ridge Regression model** predicts the FWI value.
4. The result is displayed beautifully with an animated result card on the frontend.

---

## 🧾 Requirements

```
Flask
numpy
pandas
scikit-learn
pickle
```

---

## 🧑‍💻 Author

**Nikhil Malagar**  
🎓 B.Tech CSE (AI & ML) @ B.L.D.E.A's V.P. Dr. P.G. Halakatti College of Engineering & Technology  
💡 Passionate about AI, ML, and Full-Stack Development  
## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikhil-malgar-549064262/)


---

## 💖 Acknowledgments

Special thanks to all open-source contributors and the Scikit-learn community for providing tools that make projects like this possible.

---

## 🏁 License

This project is licensed under the **MIT License** — feel free to use and modify it for your own learning or projects.
