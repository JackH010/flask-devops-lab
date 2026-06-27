Flask DevOps Lab
A diagnostic Flask application used to practice Git, GitHub, and Docker workflows.
Usage
Activate the virtual environment, install dependencies, and start the app:
cmd.venv\Scripts\activate
pip install -r requirements.txt
python app.py
The app runs on http://localhost:8080.
Endpoints

/api/health — Returns a simple {"status": "ok"} response to confirm the app is running.
/api/config — Returns the contents of config.json, including the app name, version, and description.
/api/report — Returns diagnostic information including the server hostname, Python version, and application uptime in seconds.
