# YorkU Timetable

A free, browser-based timetable tool for York University students.

Import your schedule from **York University's Plot My Timetable**, add classes manually, manage your timetable, view your schedule by day or week, and export it to **Google Calendar, Apple Calendar, Outlook, and other calendar apps**.

Everything runs in your browser — **no login, no backend, and no data sent anywhere**.

## Features

- 📋 **Import from Plot My Timetable** — Copy your York timetable and paste it into the app.
- ➕ **Add classes manually** — Create classes without importing a timetable.
- 📅 **Today view** — See today's classes, including your current and next class.
- 🗓️ **Week view** — Preview your complete weekly timetable.
- ✏️ **Edit classes** — Change course information, times, days, terms, or locations.
- 🗑️ **Delete classes** — Remove individual classes or clear your entire timetable.
- 💾 **Save your timetable** — Classes are stored locally in your browser.
- 📥 **Calendar export** — Export your timetable as a universal `.ics` file.
- 🎓 **York term dates** — Handles Fall, Winter, and Fall/Winter terms, including reading weeks and holidays.
- 📴 **Works offline** — The app uses a service worker so core functionality can work without an internet connection.
- 📱 **Installable** — Can be installed as an app on supported browsers and devices.
- 🔒 **Privacy-focused** — No account, backend, or server-side storage is required.

## How to Use

### 1. Import your York timetable

Open **Plot My Timetable** through the app and log in with your Passport York account.

Select your session and copy the tabular timetable information.

Paste it into **YorkU Timetable** and select **Parse & Review**.

Review the imported classes and add them to your timetable.

### 2. Or add classes manually

Choose **Add Manually** and enter:

- Course code
- Term
- Days
- Start and end time
- Location (optional)

### 3. Manage your timetable

Use the **Manage**, **Today**, and **Week** views to review your schedule.

You can edit or delete classes whenever your schedule changes.

### 4. Export to a calendar

When your timetable is ready, select **Download .ics**.

The resulting `.ics` file can be imported into:

- Google Calendar
- Apple Calendar
- Microsoft Outlook
- Other calendar applications supporting the iCalendar format

## Privacy

YorkU Timetable is designed to run entirely in the browser.

- No login is required for the app.
- No backend is used.
- Your saved timetable is stored in your browser's local storage.
- Timetable data is not sent to a server by the app.

You should still verify your timetable against York University's official information before relying on it.

## Technology

The application is built as a lightweight web application using:

- HTML
- CSS
- JavaScript
- Web App Manifest
- Service Worker
- Browser Local Storage
- iCalendar (`.ics`) export

No framework or backend is required.

## Important

YorkU Timetable is an independent student-built tool and is **not affiliated with York University**.

Always verify course times, locations, term dates, and other academic information against York University's official systems.

## License

This project is provided as-is for York University students and the wider York community.