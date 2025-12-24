# FlowTracker 

FlowTracker  is a single-page productivity application that combines a task manager and habit tracker in one interface.  
It is built with plain **HTML, CSS, and JavaScript**, and runs entirely in the browser with no backend dependencies.

---

## 📌 Project Overview

FlowTracker  allows users to:

- Create, edit, delete, and complete tasks.
- Assign time and priority (Low / Medium / High) to tasks.
- Track habits (e.g., Exercise, Reading, Meditation) with visual streak indicators.
- View a progress summary of completed vs pending tasks.
- See a chronological history of actions (Added, Edited, Completed, Reopened, Deleted) with timestamps.
- Toggle between light and dark mode for better usability.
- Persist all data using `localStorage`, so tasks and habits remain after page refresh or browser restart.[file:102][web:80]

This project is designed to showcase practical frontend skills and a real-world UX flow rather than just a basic to‑do list.

---

## 🧠 What this demonstrates

From a developer perspective, this project highlights:

- **State management in vanilla JavaScript**  
  Handling arrays of task and habit objects, IDs, and updates without any frameworks.

- **DOM manipulation and event handling**  
  Dynamically rendering lists, buttons, status indicators, and responding to user interactions.

- **Persistent client-side storage**  
  Using `localStorage` to store tasks, habits, and history in a structured way.

- **UI/UX considerations**  
  - Separate views for Tasks / Habits / History  
  - Progress and stats for quick understanding of productivity  
  - Theme toggle and responsive layout for better user experience.[file:102][web:74]

---

## 🚀 How to run

No installation is required beyond a modern web browser.

1. Clone or download this repository.
2. Open `index.html` (or `FlowTracker.html`) in any modern browser (Chrome, Edge, Firefox, etc.).
3. Use the interface to:
   - Add tasks with optional time and priority.
   - Track daily habits.
   - Review history and progress.

Everything runs locally in the browser and works offline because it relies on `localStorage`.

---

## 🛠 Tech Stack

- **HTML5** – structure and layout  
- **CSS3** – styling, gradients, cards, dark mode support  
- **JavaScript (ES6)** – application logic, state, DOM updates  
- **Web Storage API (`localStorage`)** – persistence layer

---

## 🔭 Potential Extensions

If extended further, FlowTracker Pro+ could include:

- Weekly/monthly calendar view for tasks and habits.
- Data export/import (e.g., JSON) for backup and syncing.
- More detailed analytics (completion rates, streak trends).
- Improved mobile‑first design and fine-tuned animations.[web:106][web:121]
