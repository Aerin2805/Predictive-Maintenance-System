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
    </ol>
<h2>Backend Setup</h2>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone <repo_url></code></pre>
        <pre><code>cd <project_directory>/backend</code></pre>
        <li>Install dependencies:</li>
        <pre><code>npm install</code></pre>
        <li>Set up MongoDB URL(/backend/.env) :</li>
        <pre><code>DB_URL = "mongodb://127.0.0.1:27017"</code></pre>
        <li>Run the backend:</li>
        <pre><code>npm start</code></pre>
    </ol>
<h2>Python environment Setup</h2>
            <ol>
                <pre><code>python3 -m venv venv  # Be sure your in Root Directory</code></pre>
        <pre><code>source venv/bin/activate  # macOS/Linux</code></pre>
        <pre><code>venv\Scripts\activate     # Windows</code></pre>
        <li>Install backend dependencies:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li>Run python file:</li>
        <pre><code>python app.py</code></pre>
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
