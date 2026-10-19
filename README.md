# Romantic Message App 💗

A mobile-first romantic proposal page inspired by the supplied reference image, but redesigned as an original advanced interactive web app.

## Features
- Responsive mobile/desktop design
- Personalized recipient name saved with localStorage
- Animated floating hearts and celebration particles
- Playful "No" button that dodges the cursor/touch
- "Yes" celebration modal
- Personal love letter modal
- Surprise message generator
- Optional romantic Web Audio chime (no external audio files)
- Remembers personalization and "Yes" state
- No framework or internet connection required

## Run locally

### Python
```bash
python3 -m http.server 8080
```
Then open:
http://127.0.0.1:8080

### Termux
```bash
cd ~/romantic_message_app
python3 -m http.server 8080
```
Open `http://127.0.0.1:8080` in your phone browser.

## Customize
Open `index.html` and edit the text inside the message cards and the `letterText` section to make the message personal.
