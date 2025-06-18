📄 README.md for seismic_data_calendar.html 

# 🌋 Mars Seismic Activity Calendar

An interactive browser-based visualization tool that displays Mars seismic activity by selecting a date. Built with HTML, CSS, and JavaScript, the project showcases seismic waveform data in a clean, sci-fi-inspired interface.

---

## 🚀 Features

- 📅 **Interactive date picker** to browse seismic data
- 🌌 **Animated starry background** for an immersive space-themed UI
- 📈 **Dynamic waveform preview** changes with the selected date
- 🧠 **Informative facts** about Marsquakes and the InSight mission
- 🎥 **Mars animation** adds visual appeal

---

## 📂 Project Structure

/
├── seismic_data_calendar.html # Main HTML + embedded JS & CSS
├── starry-background.js # Canvas-based animated star field (optional)
├── mars-video.gif # Animated image of Mars
├── /seimic graphs/ # Folder with seismic waveform images named by date


---

## 📅 How It Works

1. User selects a date using the input field.
2. A waveform image is dynamically loaded based on that date from `/seimic graphs/YYYY-M-D.webp`.
3. A descriptive message is shown, simulating seismic reading feedback.
4. Background stars are procedurally generated to simulate a cosmic environment.

---

## 🛠️ Tech Stack

- **HTML5** – structure
- **CSS3** – styling and responsive layout
- **Vanilla JavaScript** – interactivity
- **Canvas API** (in `starry-background.js`) – animated visual effects

---

## ▶️ Usage

1. Download or clone the repository.
2. Open `seismic_data_calendar.html` in a modern web browser.
3. Pick a date to see the corresponding seismic waveform image and description.

> ⚠️ Ensure the `/seimic graphs/` folder contains valid `.webp` files named as `YYYY-M-D.webp`.

---

## 🌌 Optional Enhancement

To use `starry-background.js`, connect it in the HTML using:


<canvas id="starry-background"></canvas>
<script src="starry-background.js"></script>
And make sure you add and style the canvas in the CSS.

🧠 Educational Insight
Marsquakes are vibrations in the Martian crust, recorded by missions like NASA's InSight. They offer clues about Mars' internal structure. This project visualizes such activity interactively to raise interest in planetary science.

📜 License
MIT License – Use, modify, and share freely.

👨‍💻 Developed By
Aldrin Binu and team[aaron johns,jonah pramod,namitha anna koshy,joel tv,pooja shibu]
