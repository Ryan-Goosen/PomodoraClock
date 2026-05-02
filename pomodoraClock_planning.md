# Pomodora Clock

---

## Project Identity

| Field | Value |
| ----- | ----- |
| **Name** | Pomodora Clock |
| **Project ID** | PC-2025-005 |
| **Owner** | Ryan Goosen |
| **Date Created** | 2025-01-01 |
| **Last Updated** | 2026-05-02 |

---

## Vision & Purpose

**Elevator Pitch:**
A customizable Pomodoro timer to boost productivity by breaking work into manageable time intervals.

**Long-Term Vision:**
A productivity tool with customizable timers, statistics tracking, and cross-platform availability.

**Success Metrics:**
- [x] Pomodoro timer working
- [x] Stopwatch functionality
- [x] Customizable time intervals
- [x] Standalone executable created

---

## Tech Stack

| Category | Tools / Languages |
| -------- | ----------------- |
| **Core Language** | Python |
| **Framework** | tkinter, ttkbootstrap |
| **Libraries** | pygame, pillow |
| **Tools** | uv, pyinstaller |
| **Version Control** | [Codeberg](https://codeberg.org/Ryan-Goosen/pomodoraClock) |

---

## Current State

**Phase:** Complete
**Progress:** 100%

**Recent Wins:**
- [x] GUI with ttkbootstrap styling
- [x] Timer, Pomodoro, and Stopwatch modes
- [x] PyInstaller executable created
- [x] Docker support added

**Blockers:**
- [ ] None

---

## Roadmap

### Main Objectives

1. **Core Timer** *(Complete)*
   - [x] Basic timer functionality
   - [x] Pomodoro mode (25 min work, 5 min break)
   - [x] Stopwatch mode
   - [x] Customizable intervals

2. **Packaging** *(Complete)*
   - [x] Create standalone executable
   - [x] Docker containerization

3. **Future Improvements** *(Backlog)*
   - [ ] Replace pygame with lighter sound library
   - [ ] Session statistics tracking
   - [ ] Settings persistence

### Immediate Next Steps
1. None - project complete

---

## Project Structure

```
/pomodoraClock
├── src/pomodoraClock/   # Source code
│   ├── main.py
│   ├── classes/
│   ├── assets/
│   └── config/
├── executable/          # Standalone builds
├── pyproject.toml       # UV dependencies
└── docker-compose.yml
```

---

## Notes & Decisions

**Key Choices:**
- Used ttkbootstrap for modern UI styling
- Pygame for audio notifications
- UV for dependency management

**Backlog / Ideas:**
- Replace pygame with native system sounds
- Add productivity statistics dashboard
- Export session data

**Debug Log:**

---

## Visuals

![Product Screenshot](src/pomodoraClock/assets/images/final.png)
