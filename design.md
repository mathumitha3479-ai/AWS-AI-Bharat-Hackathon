# Project Design

## Workflow:
User → Enter Data → Store Data → Risk Analysis → Generate Suggestions → Reminder Cycle
      ┌─────────┐
      │  User   │
      └────┬────┘
           │
     [Enter Data]
           │
           ▼
   ┌─────────────┐
   │ Frontend UI │
   │Flutter /    │
   │React Native │
   │HTML/CSS/JS  │
   └────┬────────┘
        │ API Calls
        ▼
   ┌───────────────┐
   │   Backend     │
   │Python Flask / │
   │Node.js        │
   │Rule-based     │
   │Risk Analysis  │
   └────┬─────────┘
        │ Store / Retrieve Data
        ▼
   ┌─────────────┐
   │  Database   │
   │Firebase /   │
   │SQLite       │
   └────┬────────┘
        │
   ┌──────────────┐
   │ Notifications│
   │ & Reminders  │
   │Email /       │
   │WhatsApp API  │
   └──────────────┘
   
## Wireframe:
- **Screen 1:** User Data Entry Form – Input fields, submit button
- **Screen 2:** Dashboard – Shows stored data and analysis summary
- **Screen 3:** Risk Analysis Results / Suggestions Page
- **Screen 4:** Reminder / Notification Settings Page
- Navigation: Simple buttons/menus to switch screens

## Technology Details:
- Frontend: Flutter / React Native / HTML/CSS/JS
- Backend: Python Flask / Node.js
- Database: Firebase / SQLite
- Notifications & Reminders: Email / WhatsApp API
- Hosting: Render / Vercel / Firebase free tier

## Notes:
- Reminder system interacts with **Backend** and **Database** for scheduling and tracking notifications.
- System is designed for **fast hackathon deployment** and low-cost implementation.

