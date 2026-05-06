# 🏏 IPL Sports Analytics Platform

An end-to-end IPL Sports Analytics and Match Prediction platform built using Machine Learning, Streamlit, Python, Scikit-learn, XGBoost, and IPL ball-by-ball datasets.

This project analyzes 16+ seasons of IPL cricket data to generate real-time match win predictions, uncover player and venue performance trends, and provide interactive cricket analytics through a modern dashboard.

---

# 🚀 Features

## ✅ Real-Time Match Win Prediction

* Predicts live win probability based on:

  * Current score
  * Target score
  * Overs completed
  * Wickets lost
  * Current Run Rate (CRR)
  * Required Run Rate (RRR)

## ✅ Machine Learning Models

Implemented and compared multiple ML models:

| Model               | Purpose                                     |
| ------------------- | ------------------------------------------- |
| Logistic Regression | Baseline generalized predictor              |
| Random Forest       | Captures nonlinear cricket match patterns   |
| XGBoost             | Advanced boosting-based predictor           |
| KMeans Clustering   | Player segmentation and role identification |

---

# 📊 Dashboard Modules

## 🏏 Live Match Predictor

Interactive match simulator for predicting live IPL match outcomes.

## 🤖 ML Model Comparison

* Accuracy comparison
* Model evaluation
* Overfitting analysis

## 🏆 Player Analytics

* Top run scorers
* Strike rate analysis
* Season-wise trends

## 🎯 Bowling Analytics

* Economy rate comparison
* Top IPL bowlers

## 🧠 KMeans Clustering

Player segmentation into:

* Power Hitters
* Anchors
* Finishers
* Low-impact batters

## 🏟 Venue Analytics

* Average first innings score
* Chasing vs defending win percentage
* Venue-specific match patterns

## ⚔ Head-to-Head Analysis

* Team vs Team comparison
* Historical win/loss records

## 📈 Season Trends

* Season-wise player performance evolution
* Strike rate trend visualization

---

# 🧠 Machine Learning Pipeline

## Feature Engineering

The following match-state features were engineered:

* Runs Left
* Balls Left
* Wickets Left
* Current Run Rate
* Required Run Rate
* Batting Team
* Bowling Team
* Match Venue

---

# 📌 Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 80.68%   |
| Random Forest       | 99.91%   |
| XGBoost             | 94.52%   |

> Note:
> Random Forest and XGBoost showed signs of overfitting due to sequential ball-level similarity in cricket match states. Logistic Regression provided the most realistic generalized performance.

---

# 🗂 Dataset Used

## IPL Ball-by-Ball Dataset

Contains:

* Ball-by-ball delivery information
* Batting performance
* Bowling performance
* Match events

## IPL Matches Dataset

Contains:

* Match metadata
* Teams
* Venues
* Toss details
* Match winners

---

# 🛠 Tech Stack

## Programming Language

* Python

## Libraries & Frameworks

* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* Streamlit

---

# 📷 Project Screenshots
<img width="1460" height="929" alt="1c1a82fabc0b3704a6adb9a400f703f9016bbe631a76c50f9047d9e3" src="https://github.com/user-attachments/assets/d20c76c5-fe6d-4fdd-9254-3dd7ccefe6d9" />
<img width="1460" height="938" alt="1424b1ae62f8e633fc2ecb1a26f2245f357b4b765d51fdfa8d302adc" src="https://github.com/user-attachments/assets/36242a3e-d050-40e3-92ca-80291d9fea6e" />
<img width="1460" height="855" alt="0aa46df40c26fa09ac75a64884a127a823979c7b641254a48bee83fe" src="https://github.com/user-attachments/assets/0a786de5-474c-43aa-bf9b-4bbaf69cd97c" />
<img width="1356" height="1200" alt="6b00764f69c72329867b650510c181a642029e079cb55003d0ac041e" src="https://github.com/user-attachments/assets/679f6ab7-1c55-419d-a6fa-66cff31aa444" />
<img width="1460" height="681" alt="3172f58ec4fefcc7fab028d75ce645bd0b66ff39bff6392e0e782f8b" src="https://github.com/user-attachments/assets/1a5f4f93-60a4-42f3-aff6-3dc3136a1c31" />
<img width="1460" height="911" alt="ee3d3208c65311b4dcabc4cafa237193bd316c384ecb4c5831540499" src="https://github.com/user-attachments/assets/0a69f13c-e34a-4d05-97ca-856739ddb8b0" />



---

# 📂 Project Structure

```bash
IPL-Sports-Analytics/
│
├── app.py
├── pipe.pkl
├── teams.pkl
├── cities.pkl
├── matches.csv
├── deliveries.csv
├── batter_clusters.csv
├── bowler_stats.csv
├── venue_analysis.csv
├── virat_stats.csv
├── requirements.txt
└── README.md
```

---

# ▶️ How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/IPL-Sports-Analytics.git
```

## 2️⃣ Navigate to Project Folder

```bash
cd IPL-Sports-Analytics
```

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 4️⃣ Run Streamlit App

```bash
streamlit run app.py
```

---

# 📌 Future Improvements

* Dark mode UI
* Team logo integration
* Real-time API integration
* Advanced player comparison system
* Match simulation engine
* Deep learning-based prediction models

---

# 💡 Key Learnings

This project helped in understanding:

* End-to-end ML workflows
* Feature engineering for sports analytics
* Supervised and unsupervised learning
* Data visualization techniques
* Interactive dashboard development
* Streamlit deployment
* Cricket data analysis

---

# 👨‍💻 Author

## Perfect

Computer Science Engineering Student

---

# ⭐ If you liked this project

Give this repository a ⭐ on GitHub and share it with others.
