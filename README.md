# 🏠 Energy Efficiency Prediction using Gradient Boosting

## 📖 About the Project

Buildings consume a significant amount of energy, and a large portion of this consumption comes from:

- 🔥 Heating during winter
- ❄️ Cooling (Air Conditioning) during summer

A poorly designed building requires more energy to maintain a comfortable indoor temperature, while an energy-efficient building reduces electricity consumption and operating costs.

This project uses **Machine Learning** to predict the **Heating Load** and **Cooling Load** of residential buildings based on their architectural characteristics.

The model was trained on the **Energy Efficiency Dataset** using the **Gradient Boosting Regressor**, which achieved the best prediction performance among the tested models.

---

# ✨ Features

- ✅ Predict Heating Load and Cooling Load
- ✅ Interactive Streamlit web application
- ✅ User-friendly sliders and input fields
- ✅ Real-time prediction
- ✅ Energy efficiency rating (Excellent / Good / Average / Poor)
- ✅ Interactive charts using Plotly
- ✅ Responsive and clean dashboard
- ✅ Fast and accurate predictions

---

# 📊 Input Parameters

The model predicts energy consumption using the following building characteristics:

- Relative Compactness
- Surface Area
- Wall Area
- Roof Area
- Overall Height
- Orientation
- Glazing Area
- Glazing Area Distribution

---

# 🤖 Machine Learning Model

**Algorithm**

- Gradient Boosting Regressor

**Libraries Used**

- Scikit-learn
- Pandas
- NumPy
- Plotly
- Streamlit
- Joblib

---

# 📈 Model Performance

Evaluation Metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

The Gradient Boosting model achieved the highest prediction accuracy compared with the other tested regression algorithms.

---

# 🚀 Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/USERNAME/energy-efficiency-prediction.git

cd energy-efficiency-prediction
```

## 2. Install dependencies

```bash
pip install -r requirements.txt
```

## 3. Run the application

```bash
streamlit run app.py
```

---

# 📁 Project Structure

```
energy-efficiency-prediction/
│
├── app.py
├── energy_model.pkl
├── requirements.txt
├── Energy_Efficiency_Final_Project.ipynb
├── house.png
├── README.md
```

---

# 📦 Dataset

**Energy Efficiency Dataset**

Input Features:

- Relative Compactness
- Surface Area
- Wall Area
- Roof Area
- Overall Height
- Orientation
- Glazing Area
- Glazing Area Distribution

Target Variables:

- Heating Load
- Cooling Load

---

# 🛠 Technologies Used

- Python
- Scikit-learn
- Streamlit
- Plotly
- Pandas
- NumPy
- Joblib
- Matplotlib
- Seaborn

---

# 📸 Application Preview

Add screenshots of your Streamlit application here.

Example:

```
images/home.png
images/prediction.png
images/charts.png
```

---

# 👨‍💻 Team

NTI Machine Learning Project
Habiba Gamal
Abdelwahab Ali
Shahd Shawkat
Amir Mustafa
Eman Abo Al Qassem


---

# ❤️ Acknowledgments

Special thanks to:

- NTI (National Telecommunication Institute)
- UCI Machine Learning Repository
- Scikit-learn Community

---

# 📄 License

This project is for educational purposes only.
