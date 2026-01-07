# SchemeAssist AI – Government Scheme Recommendation System

SchemeAssist AI is an industry-level **full-stack GovTech application** designed to intelligently recommend government welfare schemes to citizens using AI-driven eligibility analysis. The system evaluates user profiles based on income, age, location, and needs to deliver accurate, explainable, and actionable scheme recommendations.

---

## 🚀 Key Features

* AI-based eligibility scoring and scheme ranking
* Personalized government scheme recommendations
* Secure JWT-based authentication
* Role-Based Access Control (Citizen & Admin)
* Explainable AI logic (transparent decision-making)
* Clean, citizen-friendly web dashboard
* RESTful API architecture

---

## 👥 User Roles

### 👤 Citizen

* Secure login
* Profile submission (age, income, location, needs)
* View personalized scheme recommendations with eligibility scores

### 🛡️ Admin

* Secure login
* View and manage government scheme data
* Monitor system-level scheme information

---

## 🏗️ Tech Stack

**Frontend:** React (Vite)

**Backend:** FastAPI (Python)

**Authentication:** JWT, OAuth2

**AI Logic:** Rule-based eligibility scoring (ML-ready)

**Database:** Simulated dataset (extendable to PostgreSQL / MongoDB)

---

## ▶️ How to Run the Project

### Backend Setup

```bash
cd backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
uvicorn main:app --reload
```

Backend will run at:

```
http://127.0.0.1:8000
```

Swagger API Docs:

```
http://127.0.0.1:8000/docs
```

---

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend will run at:

```
http://localhost:5173
```

---

## 🔐 Demo Login Credentials

**Citizen**
Username: `citizen1`
Password: `citizen123`

**Admin**
Username: `admin1`
Password: `admin123`

---

## 🎓 Academic & Industry Context

This project was developed as an **8th Semester B.Tech (CSE / AI / AIML) industry-level project** under the **Civora Nexus Pvt. Ltd. Internship Program**.

**Project ID:** AID105
**Domain:** Artificial Intelligence / GovTech / Full-Stack Development

---

## 📌 Use Cases

* Citizen welfare scheme discovery
* Government outreach and accessibility
* AI-powered public service platforms
* GovTech startup MVP development

---

## 🔮 Future Enhancements

* Machine learning-based recommendation models
* Multilingual support (Hindi & regional languages)
* PDF eligibility report generation
* Database integration
* Cloud deployment (AWS / Azure)

---

## 👤 Author

**Yashi Lakhera**
B.Tech CSE (AI/ML)
Industry Internship Project – Civora Nexus Pvt. Ltd.

---

⭐ If you find this project useful, feel free to star the repository!
