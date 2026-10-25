# F1-Pomodoro
F1 themed Pomodoro Timer
Note on commit history: This project was developed locally in a desktop environment. Rather than pushing incremental updates during the prototyping phase, the codebase was structured locally and published as a unified release.
# 🏎️ F1 Pomodoro

> **Race control for deep work.** A high-performance, Formula 1-themed Pomodoro timer that turns productivity into a race strategy. Watch an animated F1 car lap real-world Grand Prix circuits as you power through your focus stints and pit stops[cite: 1, 18].

[![Live Demo](https://img.shields.io/badge/demo-live-e10600?style=for-the-badge&logo=formula1&logoColor=white)](https://f1-pomodoro.vercel.app/)

---

## 🌟 Key Features

* **Live Circuit Telemetry:** Watch your car navigate authentic Grand Prix track layouts (featuring all 24 rounds of the 2026 season) complete with smooth POV camera zooming, sector splits, and satellite minimaps[cite: 1].
* **2026 Paddock & Driver Customization:** Pick your constructor from all 11 official 2026 teams (Ferrari, McLaren, Red Bull, Mercedes, Aston Martin, Williams, Alpine, Haas, Audi, Racing Bulls, and Cadillac) and select your driver[cite: 18]. The entire UI theme, car livery, driver helmet color, and chassis specs adapt dynamically[cite: 18].
* **Race Control Workflow:** Structured 25-minute focus laps, 5-minute pit stops, and a 15-minute long break after completing a 4-lap block[cite: 1, 18].
* **Immersive Start Sequence:** Hitting **"Lights out"** triggers a realistic 5-light gantry sequence with authentic audio beeps before your session begins[cite: 1].
* **Persistent Telemetry & Safeguards:** Your streak, session counts, chosen circuit, and team configuration save automatically via `localStorage`[cite: 1, 18], with built-in protection against accidental tab closures mid-race.
* **Desktop Notifications & Hotkeys:** Get alerted when your stint finishes even if the tab is in the background.

---

## 🚦 How to Use It

1. **Select Your Team & Driver:** Use the **Paddock** card in the right sidebar to choose your constructor and driver[cite: 18]. Your UI accent colors and driver badge update instantly[cite: 18].
2. **Choose a Circuit:** Scroll through the **2026 Season** calendar in the sidebar and select your Grand Prix[cite: 1].
3. **Hit Lights Out:** Click **Lights out** on the main timer panel to start your stint[cite: 1]. Watch the car drive the circuit while you work[cite: 1].
4. **Box, Box (Pit Stop):** When a 25-minute lap finishes, the app automatically transitions to pit stop mode for a quick break before heading back out on track[cite: 1].

---

## ⌨️ Pit Radio Hotkeys

* <kbd>Spacebar</kbd> — Start / Pause session[cite: 1]
* <kbd>S</kbd> — Skip current phase[cite: 1]
* <kbd>R</kbd> — Reset race session[cite: 1]
* <kbd>←</kbd> / <kbd>→</kbd> — Cycle through Grand Prix circuits[cite: 1]

---

## 🛠️ Project Structure

```text
├── index.html       # Main application interface, styles, and timer logic
├── tracks.js        # SVG path geometry and metadata for all 24 F1 circuits
└── README.md        # Project documentation
