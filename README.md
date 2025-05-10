# 🎯 AI-Powered Career Guidance System

This project is a Python Full Stack-based career guidance system that intelligently recommends career paths based on a user's skills and interests. Built using Flask and deployed via ngrok, it is ideal for aspiring developers and students exploring AI applications in real life.

---

## 🚀 Features

- ✅ Accepts user input for skills and interests
- 🧠 Rule-based AI logic for career recommendations
- 🔁 Returns top 3 career matches with scoring
- 🌐 Flask backend exposed publicly via ngrok
- 📦 Modular code suitable for future ML model integration

---

## 📊 Sample Careers in Dataset

- Data Scientist
- Web Developer
- AI Researcher
- Cloud Engineer
- Business Analyst

---

## 🔧 Tech Stack

- Python 3.x
- Flask (REST API)
- Pandas
- pyngrok (public access via ngrok)
- Google Colab (for development/testing)

---

## 📂 How to Run

1. **Clone the repo** or open the `.ipynb` notebook in Google Colab
2. Install required packages:
   ```bash
   pip install flask pyngrok

3. [Optional] Add your ngrok authtoken:

ngrok config add-authtoken YOUR_TOKEN_HERE

5. Run the Flask app and copy the ngrok URL

6. Send POST requests with JSON like:
{
"skills": ["Python", "Flask"],
"interests": ["AI", "Web Development"]
}

---

🛠 Future Scope
✅ HTML + JS frontend

🤖 Switch from rule-based to ML-based predictions

🧑‍💼 Resume parsing for auto-filling user profile

📊 Admin dashboard for analytics

🤝 Contributing
Pull requests are welcome.
For major changes, please open an issue first to discuss what you’d like to change.

