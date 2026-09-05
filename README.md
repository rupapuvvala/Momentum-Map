# Momentum-Map – Study & Daily Life Planner

A smart, gamified study and daily life planner that helps students manage tasks, build habits, set weekly goals, and earn credits for focused study sessions.

## Live Demo

* **Website:** [https://rupapuvvala.github.io/Momentum-Map/](https://rupapuvvala.github.io/Momentum-Map/)

Open the link in Google Chrome (or any modern browser) to use the app directly.

## Features

* Subject-wise **task planning** with customizable timers  
* Automatic **weightage** for each task  
* **Locked focus sessions** – only one timer runs at a time  
* **Daily habit tracker** with streaks  
* **Weekly goals** module  
* **Credits & level dashboard**:
  - Today’s points  
  - Total points (all-time credits)  
  - Level progression (e.g., Level 1, Level 2, …)  
* All data stored in **browser localStorage** (no login, no server)

## Installation Requirements

* A modern web browser:
  - Google Chrome (recommended)
  - Microsoft Edge / Firefox / Safari (latest versions)
* No additional software, frameworks, or servers are required.
* Optional: A code editor (e.g., VS Code, Notepad++) if you want to edit the source code.

## Steps to Run / Execute the Project

### Option 1: Use the Live Website

1. Open: [https://rupapuvvala.github.io/Momentum-Map/](https://rupapuvvala.github.io/Momentum-Map/)  
2. Start using the planner directly:
   - Go to **Subjects** to select your class and subjects.  
   - Go to **Study** to add tasks and start timers.  
   - Use **Habits** and **Goals** to track daily and weekly targets.  
   - Check **Credits** to see your points and level.

### Option 2: From Local File (without GitHub)

1. Download / clone this repository.
2. Open `index.html` in a text editor to confirm it’s the planner code.
3. Double-click `index.html` to open it in your browser, or:
   - Right-click → **Open with** → **Google Chrome**.
4. Use the application as described above.

## How Credits Work

* Each task has:
  - A **timer** (in minutes)  
  - An automatic **weightage** (based on topic importance)  
* When the timer **completes**, credits are awarded automatically:
  - Formula (conceptual):  
    `credits ≈ (minutes / 5) × (weightage / 10)`  
* Additional credits:
  - **Daily habits**: fixed credits per habit marked done each day  
  - **Weekly goals**: bonus credits on goal completion  
* Credits increase:
  - **Today’s points**  
  - **Total points**  
  - **Level** (e.g., every 100 points = 1 level)

## Data Storage & Privacy

* All data (tasks, habits, goals, credits, settings) is stored in **localStorage** in your browser.
* Data:
  - Persists across sessions on the same device and browser  
  - Is **not** sent to any server  
* Clearing browser data will reset the app’s stored data.

## Future Enhancements (Optional)

* Add question banks for subject-wise practice tests  
* AI-based task recommendations based on performance  
* Multi-device sync with optional login  
* More detailed analytics (weekly/monthly study time, subject-wise breakdown)

## Team Details (Hackathon)

* **Team Name:** AlgoAcademics  
* **University:** Aditya University  
* **Course / Program:** B.Tech CSE (AI & ML)  
* **Academic Year:** 2025–2026  
* **Team Members:**
  1. Puvvala Rupa Devi Naga Sai  
  2. Renati Teja Gayatri  
  3. Kalisetti Manikanta  
  4. Mattaparthi Seshendra Pranith  

## Source Code

* The entire project is implemented in a single HTML file: **`index.html`** in this repository.  
* This file includes all HTML structure, CSS styling, and JavaScript logic for:
  - Study tasks with timers  
  - Habit tracker  
  - Weekly goals  
  - Credits and level system  

To run the project locally, open `index.html` in a modern browser (preferably Google Chrome).
