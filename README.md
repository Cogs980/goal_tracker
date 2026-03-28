# goal_tracker
# Mohan's Personal Dashboard

A single-page personal dashboard to track goals, daily habits, savings, tasks, and calendar – with browser notifications and an AI goal coach.

Live site: `https://YOUR_USERNAME.github.io/mohan-dashboard/`

---

## Features

- **Goals board**
  - Create goals by area (Health, Career, Finance, etc.)
  - Progress sliders, percentage badges, milestones (25 / 50 / 75 / 100%)
  - Mark goals as complete with one click

- **Calibration (⚙️)**
  - **Unit-based** tracking (e.g. glasses of water, steps, study sessions)
  - **Amount-based** tracking (e.g. save ₹10,000/month → ₹333/day)
  - One-tap log buttons and “Today’s Log” summary

- **Eisenhower Matrix**
  - Q1–Q4 quadrants (Do First, Schedule, Delegate, Eliminate)
  - Add, check off, and schedule tasks

- **Calendar**
  - Shows:
    - Daily logs (unit + amount progress)
    - Events you add
    - Tasks scheduled for each day
    - Completed-goal count per day
  - Click any day to see a detailed popup of all activity

- **AI Goal Coach (chat)**
  - Example commands:
    - `Add goal: Save ₹10,000 this month`
    - `Saved ₹500 today`
    - `Log water`
    - `Add urgent task: Call lab`

- **Browser notifications**
  - Asks once for permission
  - Notifies on:
    - Today’s events/tasks when you open the page
    - Goal milestones (25 / 50 / 75%)
    - Goal completion (100%)

---

## How to Use

1. **Add goals** in the **📊 Goals** tab.
2. Open **⚙️ Calibrate** for each goal:
   - Choose **Unit-based** (e.g. Glass, 250 ml, target 1000 ml)  
   - Or **Amount-based** (e.g. ₹, 10000/month)
3. Use **Today’s Log** area or the **log buttons** on each goal to record progress.
4. Plan tasks in **⚡ Eisenhower** and schedule them to dates.
5. Review everything in **📅 Calendar**; click a day for full history.
6. Chat with **💬 AI Coach** to add goals, log savings, or create tasks via natural language.

---

## Local Development

This is a pure static HTML app.

- No build step, frameworks, or backend.
- Just open `index.html` in a browser to use locally.

---

## Deployment (GitHub Pages)

1. Put `index.html` in the root of a public GitHub repo.
2. In the repo, go to **Settings → Pages**.
3. Source: **Deploy from a branch** → `main` → `/ (root)`.
4. Open: `https://YOUR_USERNAME.github.io/REPO_NAME/`.

---

## Notes

- Notifications only work after you **Allow** them in the browser.
- True push when the site is fully closed is **not** supported (no backend) – notifications work while the tab is open (foreground or background).

---

## For Dentists / Clinic Owners

You can also use this dashboard as a **lightweight practice KPI tracker**:

- Example **clinic goals**:
  - “50 new patients this month”
  - “₹5,00,000 collections this month”
  - “20 implants placed this quarter”
  - “Post 8 Reels and 4 long YouTube videos this month”

- **How to set them up**:
  - Category: use **Finance** for revenue, **Career** for clinical skill targets, **Hobbies** for content/branding work.
  - Use **Unit-based** calibration for:
    - Number of procedures (implants, RCTs, aligners, etc.)
    - Content outputs (videos, posts)
  - Use **Amount-based** calibration for:
    - Monthly collections / revenue
    - Monthly marketing spend caps

- **Clinic workflow ideas**:
  - Morning: check **📅 Calendar** for scheduled “Review lab orders”, “Content shoot”, “Team meeting”.
  - During the day: log **procedures or revenue** using quick buttons (e.g. +1 implant, +₹5,000).
  - Evening: glance at **Today’s Log** + notifications to see if daily targets (revenue, cases, content) are met.
