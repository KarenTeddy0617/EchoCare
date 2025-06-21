# EchoCare
💚 EchoCare: Mental Health Check-In AI Agent
EchoCare is a supportive AI companion that checks in with users daily via email, offering personalized motivational messages and a link to log their mood. It combines n8n for backend workflow automation with a clean user-friendly frontend.
💡 Features

- 🤖 **AI Agent** that generates personalized motivational messages
- 📧 **Automated Emailing** via n8n based on Google Sheets input
- 📊 **Mood Logging Interface** built with Streamlit
- 🔁 **Autonomous Check-ins** triggered at scheduled times
- 🧠 Focus on **mental well-being** through positive reinforcement

🧩 Workflow Overview

1. **User logs in** via a form (Google Forms or custom Streamlit).
2. User data (Name, Email) is stored in **Google Sheets**.
3. n8n workflow:
   - Reads user data from Google Sheets.
   - Sends it to **AI agent** to generate motivational message.
   - Emails the user with the message + mood logging link.
4. User clicks the link to open the **app** and logs their current mood.
