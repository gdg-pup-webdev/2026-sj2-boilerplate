# GDG PUP Webverse vol. 2: JavaScript & DOM Manipulation - Boilerplate

[![Status: Teaching](https://img.shields.io/badge/Status-Teaching-blue)](docs/state.md)
[![Stack: JavaScript](https://img.shields.io/badge/Stack-JavaScript-black)](#about)
[![FMD philosophy: 1.31.0](https://img.shields.io/badge/FMD%20philosophy-1.31.0-blue)](AGENTS.md)


Starter code for the Live Coding Session. During the session, we populate these files to build a Pomodoro Timer with focus modes, controls, and session tracking.

## Table of Contents

- [About](#about)
- [Start here](#start-here)
- [What these files are for](#what-these-files-are-for)
- [Quick start](#quick-start)
- [What we'll learn](#what-well-learn)
- [Code structure overview](#code-structure-overview)
- [Documentation](#documentation)
- [Contributors](#contributors)

## About

This is the starter code for the **Live Coding Session**. During the session, we will populate these files to build a **Pomodoro Timer** featuring:

- Focus, Short Break, and Long Break modes
- Start/Pause/Reset controls with live countdown
- SVG progress ring animation
- Dynamic theme colors based on mode
- Session tracking

## Start here

- **Humans:** this README, then [docs/state.md](docs/state.md)
- **Agents:** [AGENTS.md](AGENTS.md) (state → index → FLAGS)
- **Contributors:** table below

## What these files are for

| File | Description |
|------|-------------|
| `pomodoro.html` | Contains the complete HTML structure, font links, and button elements. |
| `styles/pomodoro.css` | Contains CSS variables, GDG color palette, and all styling (pre-built). |
| `js/main.js` | **The main file we'll code together!** Contains the skeleton structure with comments and hints. |

## Quick start

### Option 1: Download ZIP (Easiest)

1. Click the green **Code** button at the top of this page.
2. Select **Download ZIP**.
3. Extract (Unzip) the downloaded file to a folder on your computer.

### Option 2: Git Clone (For those with Git installed)

Open your terminal (Command Prompt or PowerShell) and run:

```bash
git clone https://github.com/gdg-pup-webdev/sj2-boilerplate.git
```

### Run locally

1. Open this folder in **VS Code**.
2. Right-click `pomodoro.html` and select **"Open with Live Server"**.
3. Follow along with the speaker!

## What we'll learn

During this session, we'll cover the following JavaScript concepts:

- **Variables & Constants** - Storing timer durations and state
- **DOM Manipulation** - Selecting and updating HTML elements
- **Functions** - Creating reusable code blocks
- **Event Listeners** - Responding to button clicks
- **setInterval / clearInterval** - Creating the countdown timer
- **Conditionals** - Handling different timer modes
- **CSS Custom Properties** - Changing theme colors with JavaScript

## Code structure overview

The `js/main.js` file is organized into 5 sections:

1. **Variables & Configuration** - Timer durations and state variables
2. **DOM Elements** - Selecting buttons and display elements
3. **Timer Functions** - `updateTimerDisplay()`, `startTimer()`, `resetTimer()`, `setMode()`
4. **Event Listeners** - Connecting buttons to functions
5. **Initialization** - Starting the app

Happy coding!

## Documentation

| Doc | Purpose |
| --- | --- |
| [State](docs/state.md) | Operate position / teaching handover |
| [Index](docs/index.md) | Document manifest |
| [FLAGS](FLAGS.md) | Improvement register |
| [AGENTS](AGENTS.md) | Agent read order |

## Contributors

This project is made possible by the GDG PUP community.

| Name | Role | GitHub |
| --- | --- | --- |
| [Carlos Jerico Dela Torre](https://www.linkedin.com/in/delatorrecj) | Chief Technology Officer (2025-2026) | [@delatorrecj](https://github.com/delatorrecj) |
| [Gerald Berongoy](https://www.linkedin.com/in/geraldberongoy) | Senior Backend Developer / Web Development Learning Head | [@geraldsberongoy](https://github.com/geraldsberongoy) |
| Randall Graida | Development |  |

