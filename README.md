# ~ Mr Robot Terminal (Simulated) ~

<p align="center">
  <em>Mr. Robot-style interactive terminal simulation — demo / portfolio-ready</em>
</p>

<p align="center">
  <a href="https://kendinefenoman.github.io/MrRobot-Terminal/" target="_blank">
    <img src="https://img.shields.io/badge/Try%20It%20Online-black?style=for-the-badge&logo=github&logoColor=white" alt="Try it Online">
  </a>
</p>

<p align="center">
  <img alt="Demo preview" src="assets/demo-preview.gif" width="720" />
</p>

## Overview

A lightweight, browser-based terminal simulation inspired by **Mr. Robot**.  
Everything is a **simulation** — no real scanning, exploitation, or network activity.  
Ideal for portfolio demos, interactive slides, or playful UI experiments.

## Features

- Matrix-style animated background  
- Typing / glitch effects and configurable typing speed  
- Persona panel with rotating Elliot-like quotes  
- Story mode with ASCII scenes (`story start`, `story next`, `story restart`)  
- Simulated shell mode: `whoami`, `pwd`, `ls`, `cat <file>`, `exit`  
- `fsociety` easter-egg + Konami code trigger (↑ ↑ ↓ ↓ ← → ← → B A Enter)  
- Glitch / flash visual + short beep audio when easter-egg triggers  
- Command autocomplete (Tab) + command history (Up / Down)  
- Dark / Green theme toggle  
- Export / copy terminal output

> ⚠️ **Important:** This is a demo. Do **not** use these commands on real systems.

## Quick Usage

- Try commands:
  - `scan target.com` (simulated)
  - `scan target.com --fast`
  - `recon` or `gobuster`
  - `exploit` (demo output)
  - `notes` / `notebook`
  - `persona` (random quote)
  - `story start` → `story next`
  - `shell` → then `whoami`, `ls`, `cat secret.txt`, `exit`
  - `fsociety` or Konami code for easter-egg
  - `help` to list commands
  - `theme toggle` to switch themes

## How to Run Locally

### 1) Open directly in your browser
- Double-click `index.html` or right-click → **Open with → Your Browser**.  
- Works on Chrome, Edge, Firefox, Safari.  
- ⚠️ Some features like audio autoplay or clipboard may require a local server.

### 2) Use a local static server (recommended)

**Python 3:**
```bash
python -m http.server 8000
# Open in browser: http://localhost:8000



