# index.html
Interactive typing lab with a responsive QWERTY virtual keyboard, color-coded left- and right-hand finger guides, live next-key hints, speed/accuracy analytics, and achievement badges.   Detailed README Overview
# TypeFlow Pro — Typing Lab

**TypeFlow Pro** is a responsive, browser-based typing practice application built with HTML, CSS, and vanilla JavaScript[cite: 1]. Designed to help users build proper touch-typing habits and track long-term improvement, it pairs timed typing tests and a full QWERTY virtual typing pad with left- and right-hand finger guidance, performance analytics, skill progression, and achievement badges[cite: 1].

---

## Features

### 1. Practice & Guided Typing Pad
- **Configurable Timed Tests**: Choose between **30 seconds**, **60 seconds**, or **2 minutes**, and switch across **Easy**, **Medium**, and **Advanced** difficulty passages[cite: 1].
- **Live Telemetry**: Real-time tracking of **WPM** (words per minute), **accuracy percentage**, **time remaining**, **error count**, and **passage completion progress**[cite: 1].
- **Responsive QWERTY Virtual Keyboard**: Full on-screen keyboard layout adapted for desktop and mobile viewports, complete with **spacebar** and **backspace** support.
- **Visual Finger & Hand Guidance**:
  - Left-hand and right-hand indicators and color-coded key assignments.
  - Highlights the **next character** to type and displays **which finger** should press it.
  - Supports **clicking virtual keys** to enter text as well as **live key highlighting** when typing on a physical keyboard.
- **Passage Controls & Online Quotes**: Generate new offline passages anytime, start or reset tests smoothly, paste-protection on the typing area, and double-click **New passage** to fetch a random quote from an external API with an automatic offline fallback[cite: 1].

### 2. Analytics & Performance Tracking
- **Summary & Figures**: Track average WPM, average accuracy, total practice time, personal best speed, latest test score, and total points (`XP`)[cite: 1].
- **Progress Charts**: Canvas-based **WPM progress** and **accuracy trend** visualizations across recent sessions[cite: 1].
- **Detailed Tables**: Session history table (date, duration, WPM, accuracy, errors, score, and level) alongside a figures and performance summary table[cite: 1].

### 3. Skills, Challenges & Rewards
- **Skill Level Progression**: Automatically categorizes typing skill across tiers (*Beginner*, *Developing*, *Intermediate*, *Advanced*, *Expert*) with a progress bar toward the next milestone[cite: 1].
- **30-Second Challenge Mode**: Quick launch into a focused 30-second speed and accuracy round to beat your personal best[cite: 1].
- **Achievement Badges**: Unlockable milestones such as *First Steps*, *Practice Streak*, *Sharp Typist*, *Speed Starter*, *Fast Fingers*, and *Typing Master*[cite: 1].

### 4. Hand & Home-Row Guide
- **Finger-to-Key Reference**: Clear left-hand and right-hand breakdowns mapping pinky, ring, middle, index, and thumb assignments on a standard QWERTY layout[cite: 1].
- **Home-Row Positioning**: Visual reference for resting fingers on `A`, `S`, `D`, `F` and `J`, `K`, `L`, `;`[cite: 1].

---

## Tech Stack
- **Frontend**: Semantic HTML5, CSS3 (Grid, Flexbox, CSS custom properties, responsive media queries), and vanilla JavaScript[cite: 1].
- **Charts**: HTML5 `<canvas>` custom chart rendering[cite: 1].
- **Storage**: Browser `localStorage` for persisting test sessions locally (up to 100 saved sessions)[cite: 1].

---

## Getting Started
1. Clone or download the repository.
2. Open the HTML file directly in any modern web browser—no build step, bundler, or backend server is required.
3. Click into the typing area or tap virtual keys on mobile/desktop to begin your first session[cite: 1].

---

## Notes & Privacy
- All saved test results, scores, and badges are stored locally in your browser via `localStorage`[cite: 1].
- Finger assignments follow a standard US QWERTY touch-typing layout; individual hand posture and keyboard layouts can vary[cite: 1].
