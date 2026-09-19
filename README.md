# Aqua Schedule

A working web prototype of **Aqua Schedule**, a focus and task-management app for college students that my team designed in CS 570 (Introduction to Human-Computer Interaction) at UW–Madison in Fall 2024. The course deliverable was a Figma prototype; this version turns the core loop into a working app.

**Live demo:** https://pangrunxi.github.io/aqua-schedule/

## What it does

- **Tasks** in one place: quick add with a category and due date, or "sync" from Canvas and Calendar (simulated). The two tasks due soonest are marked *Suggested*.
- **Focus sessions**: pick a task and a length, start, and stay on the page. Tap the timer to switch between a countdown and percent complete. Add five minutes or end early at any time.
- **A tank that grows**: every finished session adds a fish. Leaving the page for more than 15 seconds ends the session and your newest fish swims away.
- Breaks, a soft chime, two themes (Ocean and Minimal), and everything is saved in the browser, so a refresh doesn't lose a session.

## What changed from the Figma version, and why

Usability testing in the course shaped the original design (a countdown instead of a percentage timer, playful rather than punishing failure messages, a notification toggle, an ocean theme). Building the working version surfaced three more changes:

1. An interruption sends away **only the newest fish** instead of emptying the tank. Losing everything makes people quit; losing one makes them try again.
2. **Manual control**: sessions can be extended (+5 min) and ended early with a confirmation, and there is a five-minute break timer with nothing at stake.
3. **Nothing is lost by accident**: a refresh resumes the session, and leaving for a few seconds only triggers a reminder.

## How it's built

One HTML file, no framework, no backend. Built with AI-assisted coding (Claude), starting from the Figma design and the usability findings from the course. Data stays in the browser (localStorage).
