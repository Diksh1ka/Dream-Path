# Dream-Path
"Dream Path" is a career guidance platform that helps individuals find ideal career paths based on their skills, interests, and education. It offers personalized course recommendations, secure authentication, and profile management, adapting to users' evolving needs to foster continuous learning and career growth.

🚀 Features
- 🔑 User authentication (Register, Login, Logout)
- 👤 User profile creation (DOB, gender, country, state, city)
- 💾 SQLite database integration
- 🔒 Secure password hashing (Werkzeug)
- 🎨 Frontend with HTML, CSS (templates + static)
- 📝 Flash messages for errors/success updates
- 📂 Organized project structure (Flask MVC style)

📂 Project Structure
my_flask_project/
│── app.py # Main Flask app
│── setup_database.py # Initializes database tables
│── requirements.txt # Dependencies
│── site.db # SQLite database (auto-created)
│
├── templates/ # HTML templates (Jinja2)
│ ├── index.html
│ ├── register.html
│ ├── login.html
│ ├── forgot_password.html
│ ├── user_profile.html
│ ├── user_interests.html
│ ├── career.html
│ └── career11.html
│
├── static/ # CSS, JS, images
│
├── instance/ # Instance folder (auto-created by Flask for DB)
├── pycache/ # Auto-generated cache files
└── venv/ # Virtual environment (ignored in GitHub)

⚙️ Setup Instructions

1️⃣ Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

2️⃣ Create a virtual environment
python -m venv venv

3️⃣ Activate the environment
venv\Scripts\activate

4️⃣ Install dependencies
pip install -r requirements.txt

5️⃣ Setup the database
python setup_database.py

6️⃣ Run the Flask app
python app.py

7️⃣ Open in browser
http://127.0.0.1:5000/

📸 Screenshots

<img width="803" height="359" alt="image" src="https://github.com/user-attachments/assets/37d31139-e90d-47ff-abeb-ea68007dc011" />

