# Calendar Application for Communication Tracking 📅

## Objective ✨
This React-based application is designed to help companies efficiently track and manage communications with other organizations. It ensures timely follow-ups, centralized record-keeping of past interactions, and planning of future engagements.

---

## Features 🚀
### Admin Module 🛠️
1. **Company Management**
   - Add, edit, and delete companies with details like name, location, LinkedIn profile, emails, phone numbers, and comments.
   - Define default periodicity for scheduled communications.

2. **Communication Method Management**
   - Add communication methods with name, description, sequence, and mandatory flag.
   - Default methods:
     - LinkedIn Post 🖋️
     - LinkedIn Message 💬
     - Email 📧
     - Phone Call 📞
     - Other 🌟

### User Module 👤
1. **Dashboard**
   - View companies with their last five communications and next scheduled communication.
   - Color-coded highlights for overdue (🔴) and due today (🟡) communications.

2. **Interactive Features**
   - Hover tooltips for completed communication details.
   - Modal to log new communication with type, date, and notes.
   - Notifications for overdue and due communications.

3. **Calendar View** 📆
   - Visualize past and upcoming communications on a calendar.

### Reporting and Analytics Module (Optional) 📊
- Communication frequency reports.
- Engagement effectiveness dashboards.
- Overdue communication trends.
- Exportable reports (PDF/CSV).
- Real-time activity log.

---

## Setup and Deployment Instructions 🖥️

### Prerequisites 📋
- Node.js and npm installed.
- GitHub account.

### Steps to Run Locally 🏠
1. Clone the repository:
   ```bash
   git clone https://github.com/charitha-duvvuru/Calender
   ```
2. Navigate to the project directory:
   ```bash
   cd Calendar
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Access the application at `http://localhost:3000`.

### Deployment 🌐
1. Build the project:
   ```bash
   npm run build
   ```
2. Deploy on a platform like:
   - **Vercel:** Follow [Vercel deployment guide](https://vercel.com/docs/deploying).
   - **Netlify:** Follow [Netlify deployment guide](https://docs.netlify.com/).
   - **GitHub Pages:** Follow [GitHub Pages deployment guide](https://create-react-app.dev/docs/deployment/#github-pages).
3. Share the live URL.
https://unitrix.netlify.app/
---

## Testing and Validation ✅
- Ensure smooth functionality without errors.
- Test for performance and usability issues.
- Include mock data (e.g., sample companies and communication schedules) for evaluation.

---

## Application Functionality 🧩
- The application provides features like company management, communication tracking, and visual analytics.
- Color-coded highlights enhance usability.

### Known Limitations ⚠️
- Reporting and analytics module is optional and may not be fully implemented.

---

## Sample Data 📂
- Mock companies, communication methods, and schedules are pre-loaded to demonstrate the application's functionality.

---
