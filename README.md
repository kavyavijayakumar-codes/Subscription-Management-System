# Brightloop Subscription Management

    brightloop/
      backend/server.py    Python 3 API + SQLite (standard library only, no pip install)
      frontend/            index.html, style.css, app.js

## Run
    cd backend
    python server.py        # then open http://localhost:8000

The server also serves the frontend. brightloop.db is created on first run with demo data.
Demo logins: admin@brightloop.com / Admin@12345, staff@brightloop.com / Staff@12345, shop@example.com / Shop@12345.
Reset-password and invoice emails are printed in the server console; set SMTP_HOST, SMTP_PORT, SMTP_USER, SMTP_PASS, SMTP_FROM to send real mail.
