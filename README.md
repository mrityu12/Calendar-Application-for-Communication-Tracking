# React Calendar Application

This project is a **React-based Calendar Application** designed to track and manage communication with companies. It features separate modules for **Admin** and **User**, along with a reporting module for generating insights. The application incorporates modern design principles and a responsive user interface.

---

## Features

### Admin Module
- Add, update, and delete companies.
- Configure communication methods and periodicity.
- Edit company details (name and communication preferences).
- Manage a centralized list of companies.

### User Module
- Dashboard to view communications and schedules.
- Log communication details (type, date, notes).
- View overdue and upcoming communications.
- Calendar view for tracking communication history.

### Reporting Module
- Generate visual insights for communication trends.
- Display communication frequency by type.
- Overdue communication trends.
- Interactive charts using Chart.js.

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-repo/react-calendar-app.git
cd react-calendar-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to:
```
http://localhost:3000
```

---

## Dependencies

The application requires the following npm packages:

- React (`react`, `react-dom`)
- React Router DOM (`react-router-dom`)
- Chart.js (`chart.js`)
- React Chart.js 2 (`react-chartjs-2`)

Install them using:
```bash
npm install react react-dom react-router-dom chart.js react-chartjs-2
```

---

## File Structure
```
react-calendar-app/
|-- public/
|-- src/
    |-- components/
    |   |-- CalendarView.js
    |   |-- TaskModal.js
    |-- modules/
    |   |-- AdminModule.js
    |   |-- UserModule.js
    |   |-- ReportingModule.js
    |-- styles/
    |   |-- styles.css
    |-- App.js
    |-- index.js
|-- package.json
```

---

## How to Use

1. **Admin Module**:
   - Add and configure companies via the Admin dashboard.
   - Edit company details as needed.

2. **User Module**:
   - Log communication details and view them on the dashboard.
   - Use the calendar to track communication history.

3. **Reporting Module**:
   - View charts and insights to understand communication patterns.
