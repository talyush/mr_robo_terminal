# mr_robot_terminal
# ~ Mr Robot Terminal (Simulated) ~

<p align="center">
  <em>Mr. Robot-style interactive terminal simulation — demo / portfolio-ready</em>
</p>

<!-- You can replace this with a real GIF or static screenshot -->
<p align="center">
  <img alt="Demo preview" src="assets/demo-preview.gif" width="720" />
</p>

## Overview

A lightweight, browser-based terminal simulation inspired by **Mr. Robot**.  
Everything is a **simulation** — no real scanning, exploitation, or network activity. This project is ideal for portfolio demos, interactive slides, or playful UI experiments.

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

## Live demo

- To preview locally, just open `index.html` in a modern browser.
- For a nicer local experience (recommended), run a static server:

```bash
# python 3
python -m http.server 8000
# then open http://localhost:8000 in your browser
