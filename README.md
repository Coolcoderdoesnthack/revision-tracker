# Revision Tracker

A study tracker that runs entirely in your browser. No sign-up, no server, no tracking.

**Live site:** https://coolcoderdoesnthack.github.io/revision-tracker/

## Features

**Timing**
- Stopwatch or Pomodoro mode, with focus, break and long-break lengths you can change
- Pomodoro beeps and logs each focus round automatically
- The timer keeps running if you refresh or close the tab
- The time left shows in the browser tab title
- Press `Space` to start or pause
- Add a note to any session ("Chapter 4 practice questions")

**Planning**
- Exam countdown with days and weeks left, and exams within a week highlighted
- Daily goal shown as a line on the weekly chart

**Progress**
- Minutes today, last 7 days, current streak and best streak
- 7-day bar chart
- 6-month heatmap of study days, like GitHub's contribution graph
- Subject breakdown for the last 30 days

**Records**
- Session list filtered by subject, with "Show more"
- Log a session by hand for time you forgot to record
- Undo after deleting a session, subject or exam
- CSV export, copy and import (with notes) for backups or spreadsheets
- Light and dark mode, works on phones

## Run it
Open `index.html` in any browser. Your data is stored in that browser (localStorage), so export a CSV now and then as a backup.

## Put it online with GitHub Pages
1. Go to **Settings → Pages** in this repo.
2. Under **Branch**, pick `main` and `/ (root)`, then **Save**.
3. After a minute or two it's live at `https://<your-username>.github.io/revision-tracker/`.

Built with plain HTML, CSS and JavaScript in a single file.
