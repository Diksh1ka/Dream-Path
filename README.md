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
<img width="812" height="355" alt="image" src="https://github.com/user-attachments/assets/359f8d5b-5866-4a1a-8fe7-890ca69b1b5e" />
<img width="760" height="338" alt="image" src="https://github.com/user-attachments/assets/b5f31362-37e5-4cee-952c-9adfb0900a30" />
<img width="753" height="339" alt="image" src="https://github.com/user-attachments/assets/1aed43ee-8603-4775-a344-31ad95ce8181" />
<img width="781" height="345" alt="image" src="https://github.com/user-attachments/assets/b85e5500-6fec-4602-87b1-d3f56f8f84ba" />
<img width="777" height="341" alt="image" src="https://github.com/user-attachments/assets/801c62df-62c3-448a-a56a-0c408eacca2c" />
<img width="777" height="346" alt="image" src="https://github.com/user-attachments/assets/301d4f31-0a39-414c-906a-cfbd0698cc39" />
<img width="790" height="344" alt="image" src="https://github.com/user-attachments/assets/823b61e7-f8b9-4c3e-95d3-77d1cb7fd526" />
<img width="738" height="327" alt="image" src="https://github.com/user-attachments/assets/59264a54-2df9-40cf-b026-7abc7f31ce78" />
<img width="737" height="331" alt="image" src="https://github.com/user-attachments/assets/e9cacc25-03d9-48b6-bb13-5d71a5ec87ad" />
<img width="700" height="331" alt="image" src="https://github.com/user-attachments/assets/b4c9b0f5-801f-4d8d-977d-5466c669c03a" />




