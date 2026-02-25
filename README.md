# MyGardens 2.0 🌱

A pixel-art productivity app/game where tasks and focus sessions grow (or wither) your garden.

## Concept

MyGardens combines:
- **Forest-like focus feedback** (focus → growth)
- **Notion-like task organization** (tasks by category/garden)

Your behavior becomes a visible ecosystem:
- ✅ Complete task → healthy plant
- ❌ Incomplete/Fail task → withered plant
- Over time, each garden reflects your work patterns

---

## Current Prototype Features

### Core Views
- **Forest View**
  - Multi-garden overview (Academic, Health, Work, Social, Growth, Creative)
  - Click a garden island to jump to its garden view
  - Ambient clouds + light floating animation
  - Region vitality labels

- **Garden View**
  - Isometric pixel tile map
  - Plants rendered by task outcome
  - Click plant to open details modal
  - Floating focus session widget (top-right)

### Task System
- Task categories (garden-based)
- Category-filtered task list (shows only active garden tasks)
- Per-task controls:
  - Complete (healthy)
  - Incomplete (withered)
  - Delete
- Focus icon per task + selection state

### Focus Session
- Floating circular widget in garden view
- Adjustable duration slider
- Start / Pause / Complete / Fail icon controls
- Clicking plant opens details (not start focus)

### Feedback & Visuals
- Healthy/withered plant variants
- Particle feedback (spark/dust)
- Pixel cloud decorations
- Category color-temperature variation in forest

---

## Tech Stack

- **Single-file web prototype**: `mygardens.html`
- Pure **HTML + CSS + JavaScript**
- No backend required for prototype
- Local persistence via browser localStorage

---

## Run Locally

### Option A: Open directly
Double-click `mygardens.html` in browser.

### Option B: Local static server (recommended)
```bash
python3 -m http.server 8000
```
Then open:
- `http://localhost:8000/mygardens.html`

---

## Project Structure

- `mygardens.html` → main app (UI, logic, rendering)
- `README.md` → project documentation

---

## Git / Deployment Notes

To publish to GitHub:
```bash
git init
git add .
git commit -m "Initial MyGardens app"
git branch -M main
git remote add origin https://github.com/<your-username>/MyGarden2.0.git
git push -u origin main
```

Optional: enable GitHub Pages for static hosting.

---

## Roadmap Ideas

- Ring-based duration picker (true circular drag)
- Seasonal palettes (spring/summer/autumn/winter)
- Day/night cycle
- Better sprite atlas pipeline (Aseprite export)
- Backend sync (users, sessions, cloud save)

---

## License

Prototype/demo use. Add an explicit license (MIT recommended) before public distribution.
