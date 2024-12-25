# cinematic-curator
An AI-powered web application that recommends movies based on your emotional state, built with Flask, OpenAI, and MailerSend.

## Features 

- Emotion analysis through natural language processing
- AI-powered movie recommendations using OpenAI's GPT-3.5 Turbo
- Rich movie details from The Movie Database (TMDb)
- Email notifications with personalized recommendations via Twilio SendGrid
- Modern, responsive UI with Tailwind CSS

## How to run the Application

1. Make sure your virtual environment is activated:
```bash
# On Mac:
source venv/bin/activate
```

2. Start the Flask application:
```bash
python app.py
```

3. The application will start and display something like:
```
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
* Restarting with stat
* Debugger is active!
* Debugger PIN: xxx-xxx-xxx
```

4. Access the application:
   - Open your web browser
   - Navigate to `http://127.0.0.1:5000` or `http://localhost:5000`
   - You should see the main page with a text area to describe your mood
