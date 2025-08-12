# 🎧 AudioSphere

**AudioSphere** is a Spotify-powered music streaming web application built using **Flask** (backend) and **HTML/CSS/JS** (frontend). It lets users search and stream music, explore artists and genres, and securely sign up or sign in to personalize their experience.

Live Demo: [https://audiosphere-l50j.onrender.com/](https://audiosphere-l50j.onrender.com/)

##  Features

-  **Search** for Songs, Artists, and Albums
-  Browse by **Genres** and **Top Artists**
-  User **Sign Up / Sign In**
-  **Profile Page** with user info
-  In-browser **Audio Player**
-  Backend with **Flask** + SQLite3
-  Uses **Spotify Web API** for music data


## Tech Stack

| Layer      | Tools & Libraries                |
|------------|----------------------------------|
| Frontend   | HTML5, CSS3, JavaScript
| Backend    | Flask (Python)                   |
| Auth       | Flask  
| Database   | SQLite3                          |
| APIs       | Spotify Web API                  |
| Hosting    | Render



##  Setup Instructions

### Prerequisites
- Python 3.10+
- Spotify Developer Account
- A virtual environment manager (like `venv` or `pipenv`)

cd AudioSphere

1. Set Up Environment

python3 -m venv venv

venv\Scripts\activate on Windows

pip install -r requirements.txt

2. Configure Spotify API
Create a .env file and add your credentials:

CLIENT_ID=your_spotify_client_id
CLIENT_SECRET=your_spotify_client_secret
Get your Spotify credentials here: https://developer.spotify.com/dashboard

3. Run the App Locally

python main.py

Visit: http://localhost:5000

# Authentication Notes

User credentials are securely stored with hashed passwords (werkzeug.security).

Sessions and Flash messages were removed for stateless compatibility on platforms like Render.

User info is passed via query parameters for profile rendering.

# Folder Structure

AudioSphere/
│
├── static/                
├── templates/            
│   ├── home.html
│   ├── signup.html
│   ├── signin.html
│   ├── profile.html
│   └── ...
├── instance/
│   └── users.db           
├── main.py                
├── requirements.txt       
└── README.md

# Deployment :

   [https://audiosphere-l50j.onrender.com/](https://audiosphere-l50j.onrender.com/)
  
# Ceated By :
Siddartha Kallampalli

Abhilash Mellacheruvu

# Future Enhancements :

Add playlists & favorites

Add messaging/comments

Make it fully mobile responsive

Add lyrics or recommendations

Enjoy streaming with AudioSphere! 

we are open for feedback contact us :

# ontact & Support

Have questions, feedback, or need help?

- **Name**:  K Siddartha

- **Email**: siddarthakallampalli70@gmail.com

- **Phone**: +91-6305323077

- **LinkedIn**: [https://www.linkedin.com/in/K Siddartha]()

- **GitHub**: [github.com/SiddarthaKallampalli](https://github.com/SiddarthaKallampalli)

Feel free to open an issue if something isn't working right.
