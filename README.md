# Daylight

A task tracker that keeps work and family time apart.

Daylight is a single, self-hostable HTML file for keeping track of your own tasks. Tasks go into two lists, **Work** and **Personal**. The page also follows how your day actually runs: work gets its hours, and time at home stays yours. There's no account, server, build step or package to install. Open `index.html` in a browser and start adding tasks.

## Why

Most to-do apps treat every task the same and leave work open around the clock. Daylight starts from a different idea: family time matters as much as a work deadline, and a day needs an end. The page shows where you are in your day, nudges you to pick a few things that matter, and lets you put work away when it's time to stop.

## Two ways your day can run

The first time you open Daylight, it asks how your work day runs:

- **Set hours, then a hard stop.** Work has fixed hours, and after they end the evening belongs to family. Once work hours are over, the Work list folds away. You can peek at it if you really need to, and then put it away again.
- **On and off through the day.** Work and family time mix, and you switch between them as you go. You pick a day start, a day end and a daily work-hours budget (0 means no limit). A Working / Family time switch at the top of the page tracks each stretch, and the arc fills in as the day goes on.

You choose your work days and a light, dark or match-your-device theme in the same place. All of it can be changed later from Settings.

## Features

- **Work and Personal lists**, each sorted into Must, Should and Later. Done tasks gather at the bottom, and you can clear them.
- **Today's three:** pin up to three tasks you most want to finish today.
- **Quick add:** type `#work` or `#personal` to sort a task as you add it, and end it with `!` to mark it Must. Press **N** anywhere to start a new task.
- **Brain dump:** paste or type many tasks at once, one per line, and they're added in one go.
- **Focus timer:** blocks of 5, 15, 25 or 50 minutes, plus a 5-minute break. Attach a task to the timer and the focus time is logged on that task.
- **Momentum:** tasks done today, minutes focused, your day streak, and a two-week history.
- **Gentle nudges:** prompts when the list gets too long or you've worked a long stretch without a break, plus a rotating productivity tip.
- **Inline editing:** click a task's title to edit it.

## Your data

Everything is stored in your browser's `localStorage`. Nothing leaves your device.

- Use **Settings → Export backup** now and then to save a `.json` copy, and **Import backup** to restore it (on this browser or another one).
- **Delete all data** wipes tasks, history and settings from this browser.
- If the browser blocks storage (some private windows or embedded previews do), Daylight shows a warning, and your tasks are cleared when the page closes.

## Running it

Pick whichever suits you:

- **Locally:** double-click `index.html`.
- **Self-hosted:** put `index.html` on any static host (GitHub Pages, Netlify, an nginx folder, and so on). It's one file. The only thing it loads from outside is its fonts, from Google Fonts. Offline, it falls back to system fonts and still works.

Each browser and each host keeps its own separate data, so stick to one, or move between them with Export and Import backup.

## Accessibility

Daylight works with the keyboard, labels its controls for screen readers, follows your device's light or dark setting, and respects reduced-motion preferences.
