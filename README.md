🚀 AgentWatch — Startup Guide

Open 3 Command Prompt windows one by one

Window 1 — Start the Backend
give one by one and click enter

cd agentwatch\backend

venv\Scripts\activate

python -m uvicorn main:app --reload --port 8000

Wait until you see:
Application startup complete.

Window 2 — Start the Malicious Page

cd agentwatch\simulation

npx serve -p 5500

Wait until you see:

Serving!
Local: http://localhost:5500

Window 3 — Start the Frontend

cd C:\Users\SURENDAR\agentwatch\frontend\agentwatch-ui

npm start

Wait until browser opens automatically at http://localhost:3000
If browser doesn't open automatically, manually go to http://localhost:3000

▶ Run the Demo

Browser open at http://localhost:3000
Click ▶ Run Agent
Watch it go green → yellow → red
Forensic diff + ArmorIQ status appears at bottom

always start in this order for a better conclusion :

Backend first → Simulation second → Frontend third
That's it.
3 windows, 3 commands each, one button click.
