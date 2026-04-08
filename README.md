⚠️ Note: This project uses Chrome Extension Manifest V2, which is now deprecated. It is kept for demonstration of architecture and functionality.

# Chrome Productivity Extension (To-Done Rocket)

⚠️ Note: This project uses Chrome Extension Manifest V2 (deprecated). It is maintained to demonstrate extension architecture, browser APIs, and task management logic. Migration to Manifest V3 is planned.

---

## Overview
A productivity-focused Chrome extension that enables users to manage tasks, track progress, and capture resources directly from the browser. The project demonstrates practical use of Chrome Extension APIs, local state persistence, and event-driven UI updates.

---

## Features
- Task management (create, complete, delete)
- Progress tracking with completion percentage
- Quick-add presets (e.g., gym, meditation)
- Capture current browser tab as a task
- Time-based dynamic greeting
- Automatic removal of completed tasks after 24 hours

---

## Tech Stack
- JavaScript (ES6+)
- Chrome Extension APIs
- HTML / CSS

---

## Architecture
- **Chrome Extension APIs** for tab access and runtime interaction  
- **Local Storage API** for persistent task management  
- **Event-driven UI updates** based on user actions  
- Modular structure separating task logic and UI rendering  

---

## Installation

Clone the repository:
```bash
git clone git@github.com:chanqoDev/To-Done-Rocket-Extension.git
```

Load into Chrome:

Open chrome://extensions/
Enable Developer Mode
Click Load unpacked
Select the project directory

## Live Extension

https://chrome.google.com/webstore/detail/to-done-rocket-planner/nnmfajngjkedfjodhldodbbnmbdjkchk

### Highlights
Built a fully functional Chrome extension using browser APIs
Implemented persistent task state with lifecycle management
Integrated browser context (tabs) into a productivity workflow

### Future Improvements
Migrate to Manifest V3
Add cloud sync for cross-device persistence
Improve UI/UX and performance
Introduce task categorization and filtering
