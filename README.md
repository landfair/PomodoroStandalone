# Pomodoro Task Manager

A productivity app that combines the Pomodoro Technique with task management. Stay focused, track your work sessions, and manage your to-do lists all in one place.

## 🚀 [Live Demo](https://landfair.github.io/PomodoroStandalone/)

## ✨ Features

### Pomodoro Timer
- **Customizable work sessions** (5-60 minutes)
- **Short breaks** (1-15 minutes)
- **Long breaks** (10-30 minutes) after completing multiple sessions
- **Configurable sessions** before long break (2-6 sessions)
- Visual progress indicator and session counter
- Browser notifications when sessions complete

### Task Management
- **Multiple lists** - Create separate lists for different projects
- **Task organization** with nested subtasks
- **Deadlines** - Set and categorize by urgency (today, this week, overdue, etc.)
- **Task completion tracking** with progress counter
- **Expandable/collapsible** subtasks for complex projects

### List Sharing & Templates
- **Share lists** via email, download as JSON, or copy to clipboard
- **Import/Export** lists with smart duplicate handling
- **Pre-built templates** for common projects (essays, shopping, work tasks)
- **Drag-and-drop upload** for importing shared lists

### Customization
- Toggle between **strikethrough or hide** completed tasks
- Switch between list and deadline views
- Persistent settings stored locally
- Clean, distraction-free interface

## 🎯 How to Use

### Getting Started
1. **Create your first list** or choose from templates
2. **Add tasks** using the input field at the bottom
3. **Set the timer** and click play to start a work session
4. **Take breaks** when the timer completes
5. **Check off tasks** as you complete them

### Keyboard Shortcuts
- **Enter** - Add a new task
- **↑ ↑ ↓ ↓ ← → ← → B A** - Easter egg! 🎮

### Sharing Lists
Click the **share button** (📤) on any list to:
- Send via email with instructions
- Download as a .json file
- Copy data to clipboard

Recipients can upload shared lists using the **Upload List** option in the header menu.

## 🛠️ Tech Stack

- **Pure HTML/CSS/JavaScript** - No frameworks, no build process
- **Font Awesome** - Icons
- **Playfair Display** - Typography (with NYU Perstare fallback for local use)
- **LocalStorage API** - Data persistence
- **Notification API** - Session completion alerts

## 📱 Installation

### Use Online
Simply visit the [live demo](https://landfair.github.io/PomodoroStandalone/) - no installation needed!

### Use Offline
1. Download `index.html`
2. Open it in any modern web browser
3. All your data saves automatically in your browser

### Chrome Extension Version
Looking for the Chrome extension? The extension files are also included in this repository:
- `manifest.json`
- `popup.html`, `popup.css`, `popup.js`
- `background.js`
- Icon files

**To install the extension:**
1. Open Chrome and go to `chrome://extensions/`
2. Enable "Developer mode" (top right)
3. Click "Load unpacked"
4. Select the PomodoroMode folder

## 💾 Data & Privacy

- All data stored **locally in your browser** (localStorage)
- **No server**, no tracking, no analytics
- **No account required**
- Export your data anytime using Download List feature

## 🎨 Credits

- Designed and developed by [Alex Landfair](https://github.com/landfair)
- Typography: NYU Perstare (local) / Playfair Display (web fallback)
- Icons: Font Awesome
- Color scheme: NYU Violet (#57068c)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Note on Fonts:** This app uses NYU Perstare font when available locally. When accessed via the web, it falls back to Playfair Display. The proprietary NYU font files are not included in this repository.

## 🐛 Found a Bug?

Please [open an issue](https://github.com/landfair/PomodoroStandalone/issues) with:
- What you expected to happen
- What actually happened
- Steps to reproduce

---

Made with ☕ and 🍅 (pomodoros)
