# Aqua Schedule

A working web prototype of **Aqua Schedule**, a focus and task-management app for college students that my team designed in CS 570 (Introduction to Human-Computer Interaction) at UW–Madison in Fall 2024. The course deliverable was a Figma prototype; this version turns the core loop into a working app.

**Live demo:** https://pangrunxi.github.io/aqua-schedule/

## What it does

- **Tasks** in one place: quick add with a category and due date. The two tasks due soonest are marked *Suggested*. The "Sync" button is a demo that adds sample tasks; a real version would connect to Canvas and Google Calendar through their APIs.
- **Focus sessions**: pick a task and a length (or set your own), start, and stay on the page. Tap the timer to switch between a countdown and percent complete. Add five minutes, take a short break, or end early.
- **A tank that grows**: every finished session adds a fish. Leaving the page for more than 15 seconds ends the session and your newest fish swims away.
- Two themes, a soft chime when a session ends, and everything is saved in the browser, so a refresh doesn't lose a session.

Built with AI-assisted coding (Claude) from the Figma design and the usability findings from the course. One HTML file, no backend.
