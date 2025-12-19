# 🦖 Dino Game

#### Live Demo 
🔗 [https://britneylu.github.io/dino-game/](https://britneylu.github.io/dino-game/)

A browser version of the Chrome Dino game.

--- 

### Important
**Images and audio are NOT loaded from local files.**  
All sprites and sounds are embedded directly in `index.html` using **Base64 data URLs** (this is how Chrome’s offline Dino game works).

---

### What this means
- No images are fetched from `static/img`
- No audio is fetched from `static/audio`
- Everything is decoded in-memory from Base64
- The game works fully offline

---

### Files
- `index.html` – main page + Base64 images & audio
- `static/css/style.css` – styling
- `static/js/dino.js` – game engine
- `static/js/main.js` – game startup

---

### Controls
- **Space / ↑** — jump
- Game starts on first key press

---

### Notes
If you want to change sprites or sounds, you must replace the Base64 strings.  
Just changing file paths will not work.

---

### Browser
Works best in Chrome. Audio requires user interaction.