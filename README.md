# FocusFlow

FocusFlow is a responsive personal productivity and habit tracking web application designed to help users organize daily routines, track habits, manage schedules and goals, monitor water intake, maintain personal notes, and analyze productivity progress.

The current version is a client-side web application built as a single `index.html` file with browser-based data persistence using LocalStorage.

## 🌐 Live Demo

https://vikasreddychaduvu.github.io/FocusFlow/

## ✨ Features

### 📊 Productivity Dashboard
- Daily productivity overview
- Completed and pending task statistics
- Overall progress percentage
- Current habit streak
- Daily water intake
- Weekly progress visualization

### ✅ Habit Tracking
- Create new habits
- Edit existing habits
- Delete habits
- Assign categories
- Set habit priorities
- Track daily habit completion
- Monthly habit tracking view
- Habit streak calculation

### 📅 Schedule Management
- Create daily schedule items
- Configure start and end times
- Assign activity categories
- Create custom categories
- Edit scheduled activities
- Delete scheduled activities

### 🎯 Goals
- Create weekly goals
- Checkbox-based goals
- Numeric progress goals
- Track goal completion
- Progress-based goals

### 💧 Water Tracking
- Add predefined water amounts
- Add custom water amounts
- Remove recorded water intake
- Track daily water consumption

### 📝 Personal Notes
- Write daily notes and reflections
- Automatically save notes locally
- Persistent notes using browser storage

### 📈 Analytics
- Monthly productivity analytics
- Yearly productivity analytics
- Completion-rate charts
- Habit distribution visualization
- Interactive data visualization using Chart.js

### 👤 Profile
- Personal profile information
- Name
- Date of birth
- Height
- Weight
- Bio
- Avatar image URL
- Current habit streak

### ⚙️ Settings
- Light and dark themes
- Water reminder settings
- Local data backup
- JSON data export
- JSON data import
- Reset application data

### 📱 Responsive Design

FocusFlow is designed to work across:

- Desktop
- Laptop
- Tablet
- Mobile devices

## 💾 Data Storage

FocusFlow currently uses the browser's **LocalStorage API** for client-side data persistence.

Application data includes:

- Profile information
- Application settings
- Habits
- Habit completion records
- Schedules
- Weekly goals
- Water intake
- Personal notes

Data is stored locally in the user's browser and is not currently synchronized with a remote server or cloud database.

## 🔄 Backup & Restore

FocusFlow provides a JSON-based backup and restore system.

Users can:

1. Export application data as a JSON file.
2. Store the backup locally.
3. Import the JSON file later to restore their data.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Tailwind CSS
- Chart.js
- Font Awesome
- Browser LocalStorage API
- JSON

## 🏗️ Architecture

The current version follows a client-side architecture:

```text
User
 │
 ▼
FocusFlow Frontend
 │
 ├── HTML
 ├── CSS
 └── JavaScript
 │
 ▼
Browser LocalStorage
 │
 └── User Application Data
