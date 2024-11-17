<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Predictive Maintenance System - Setup</title>
</head>
<body>
    <h1>Predictive Maintenance System - Setup</h1>
    
    <h2>Frontend Setup</h2>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone <repo_url></code></pre>
        <pre><code>cd <project_directory>/frontend</code></pre>
        <li>Install dependencies:</li>
        <pre><code>npm install</code></pre>
        <li>Run the frontend:</li>
        <pre><code>npm start</code></pre>
        <p>Frontend will be available at <strong>http://localhost:3000</strong></p>
    </ol>

    <h2>Backend Setup</h2>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone <repo_url></code></pre>
        <pre><code>cd <project_directory>/backend</code></pre>
        <li>Create and activate virtual environment:</li>
        <pre><code>python3 -m venv venv</code></pre>
        <pre><code>source venv/bin/activate  # macOS/Linux</code></pre>
        <pre><code>venv\Scripts\activate     # Windows</code></pre>
        <li>Install backend dependencies:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li>Set up MongoDB URL:</li>
        <pre><code>MONGO_URL = "mongodb://localhost:27017"</code></pre>
        <li>Run the backend:</li>
        <pre><code>python app.py</code></pre>
        <p>Backend will be available at <strong>http://127.0.0.1:5000</strong></p>
    </ol>

    <h2>Telegram Notifications Setup</h2>
    <ol>
        <li>Create a bot on Telegram via BotFather and get the token.</li>
        <li>Get your chat ID by sending a message to your bot and retrieving it from:</li>
        <pre><code>https://api.telegram.org/bot<TOKEN>/getUpdates</code></pre>
        <li>Update the backend with the bot token and chat ID:</li>
        <pre><code>TOKEN = "&lt;YOUR_BOT_TOKEN&gt;"</code></pre>
        <pre><code>CHAT_ID = "&lt;YOUR_CHAT_ID&gt;"</code></pre>
    </ol>

    <h2>Running the Application</h2>
    <p>Frontend: <strong>http://localhost:3000</strong></p>
    <p>Backend: <strong>http://127.0.0.1:5000</strong></p>

    <h2>Future Scope</h2>
    <ul>
        <li>Advanced model enhancements (Deep Learning)</li>
        <li>Real-time IoT integration</li>
        <li>Mobile application</li>
        <li>Cloud deployment (AWS, Google Cloud, Heroku)</li>
    </ul>

    <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
</body>
</html>
