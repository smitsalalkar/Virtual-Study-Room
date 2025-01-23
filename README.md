# Virtual Study Room

This is a simple web-based application for collaborative studying. Users can log in, create study rooms, and share notes in real-time.

# Features
- User authentication system.
- Create and join study rooms.
- Real-time collaborative notes using WebSockets.
- Persistent storage with SQLite.

# How to Run
1. Install dependencies:
   bash
   pip install flask flask-socketio flask-sqlalchemy
   
2. Run the app:
   bash
   python app.py
   
3. Open `http://127.0.0.1:5000` in your browser.

# Folder Structure
- `app.py`: Main Flask application.
- `templates/`: Contains HTML templates for the app.
- `data.db`: SQLite database file.

# License
This project is open-source and free to use.
