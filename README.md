
# 🎯 Personalized Course Recommendation System

A smart web platform that delivers **tailored course suggestions** using **Collaborative Filtering** and **Content-Based Filtering** algorithms. Built with **Flask** and a **responsive interface**, it dynamically displays relevant course data and integrates external content from **Coursera** and **Udemy**, enhancing the overall learning experience.

---

## 📌 Features

* 🔐 **User Authentication** with profile management
* 🧠 **Hybrid Recommendation Engine**

  * Content-Based Filtering
  * Collaborative Filtering
* 🌐 **Udemy/Coursera Integration**
* 📋 **Dynamic Course Listings** based on interests/preferences
* 💬 **User Feedback System** for continuous improvement
* 📱 **Responsive UI** for desktop and mobile users
* 🧾 **SQLite Database** for lightweight, efficient storage

---

## ⚙️ Tech Stack

| Layer         | Technology            |
| ------------- | --------------------- |
| Frontend      | HTML, CSS, JavaScript |
| Backend       | Python (Flask)        |
| Database      | SQLite                |
| External APIs | Udemy, Coursera       |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/course-recommendation-system.git
cd course-recommendation-system
```

### 2. Create & Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

Visit the app at: `http://127.0.0.1:5000/`

---

## 🧠 How Recommendations Work

| Type          | Description                                                           |
| ------------- | --------------------------------------------------------------------- |
| Content-Based | Matches course attributes with user interests/preferences             |
| Collaborative | Analyzes user behavior & similarity to suggest what other users liked |

---

## 📂 Folder Structure

```
├── static/                # CSS, JS, images
├── templates/             # HTML templates (Jinja2)
├── app.py                 # Main Flask app
├── models.py              # Database models (SQLite)
├── recommendation.py      # Recommendation logic
├── utils/                 # API handlers, helper scripts
├── requirements.txt       # Python dependencies
└── README.md              # You're here!
```

---

## 🧪 User Flow

1. Sign up / Log in
2. Set interests & preferences
3. Get course recommendations
4. Rate & review courses
5. Continuously updated suggestions based on interaction

---

## 🧠 Future Enhancements

* 🔍 Advanced filters (difficulty, rating, duration)
* 📈 Admin dashboard & analytics
* 🌩️ Cloud deployment (Heroku/Render/AWS)
* 📧 Email notifications for new course suggestions

---

## 👨‍💻 Author

**\Pavithra Kumaravelu**
📧 Email: [pavivel2004@gmail.com](mailto:pavivel2004@gmail.com)
🌐 GitHub: [@Pavithra-kumaravelu](https://github.com/Pavithra-kumaravelu)
