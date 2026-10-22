# Harmonix — Modern Web Music Player

[![CodeAlpha Internship](https://img.shields.io/badge/CodeAlpha-Internship%20Project-6366f1?style=for-the-badge&logo=codeforces&logoColor=white)](https://github.com/Devansh-Yadav22/codealpha-music)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

An immersive, glassmorphism-styled web audio player built with vanilla HTML5, CSS3, and modern JavaScript (ES6+). Featuring real-time **Web Audio API visualizers**, dynamic acoustic effects (Bass Boost, Space Reverb, and Procedural Synthesizer), local drag-and-drop audio imports, and full playlist management.

> **Project Origin**: Developed by **Devansh Yadav** as part of the **CodeAlpha Web Development Internship**.

---

## 🌟 Key Features

### 🎵 1. Complete Playback & Playlist Management
- **Full Player Controls**: Play, Pause, Previous, Next, Dynamic Progress Bar with scrubbing and hover timestamp tooltip.
- **Playback Modes**: 
  - **Shuffle**: Randomizes playlist queue seamlessly.
  - **Repeat Modes**: Cycle between *Off*, *Repeat All*, and *Repeat Current Track* with visual badge indicator.
- **Volume & Mute**: Slider control with instant mute/unmute toggle.
- **Instant Search**: Real-time filtering across track titles and artists.
- **Genre Filtering**: Filter by genres (*All*, *Synthwave*, *Lofi*, *Ambient*, *Imported*).
- **Favorites System**: Heart/unheart tracks with dynamic state tracking.

### 📂 2. Local Audio Track Import
- **Drag & Drop**: Drag `.mp3`, `.wav`, or other audio files directly onto the drop zone to load them instantly.
- **File Browser**: Click to select single or multiple audio files from your computer.
- **Dynamic Metadata & Duration**: Automatically inspects audio files, creates object URLs, calculates duration, and adds them to the playlist under the "Imported" category.

### 📊 3. Real-Time Canvas Audio Visualizers
Powered by the **Web Audio API** (`AnalyserNode`) and HTML5 `<canvas>` rendering at 60 FPS:
- **Circular Glow**: Radial frequency ring with pulsing bass expansion and ambient neon aura.
- **Frequency Bars**: Spectrum analyzer bars with vertical gradient and frequency peak reactivity.
- **Fluid Waveform**: Oscilloscope time-domain waveform displaying direct acoustic audio vibrations.

### 🎛️ 4. Sound & Display Laboratory (Audio FX)
- **Bass Boost**: Low-shelf `BiquadFilterNode` boosting lower frequencies for enhanced bass response.
- **Space Reverb**: Multi-node feedback delay simulation creating spacious ambient reverb.
- **Synth Beat (Procedural Synthesizer)**: Built-in 8-step sequencer and arpeggiator generating algorithmic synth loops directly using Web Audio oscillators.

### 🎨 5. Glassmorphism Design & Animations
- Dark futuristic theme with ambient blurred neon orbs.
- Interactive spinning vinyl record artwork linked to playback state.
- Micro-interactions, smooth hover transitions, and toast notifications.

### ⌨️ 6. Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>Space</kbd> | Play / Pause |
| <kbd>←</kbd> (Left Arrow) | Rewind 10 seconds |
| <kbd>→</kbd> (Right Arrow) | Fast-forward 10 seconds |
| <kbd>↑</kbd> (Up Arrow) | Increase volume (+5%) |
| <kbd>↓</kbd> (Down Arrow) | Decrease volume (-5%) |
| <kbd>M</kbd> | Toggle Mute |
| <kbd>S</kbd> | Toggle Shuffle |
| <kbd>R</kbd> | Cycle Repeat Mode |

---

## 📁 Project Structure

```text
codealpha-music/
├── index.html       # Application markup and semantic layout
├── styles.css       # Glassmorphism design system, layout, and animations
├── app.js           # Audio engine, Web Audio API graph, Visualizer, FX & UI logic
└── README.md        # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
Any modern web browser supporting HTML5 and Web Audio API (Google Chrome, Mozilla Firefox, Microsoft Edge, Brave, Safari).

### Running Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Devansh-Yadav22/codealpha-music.git
   cd codealpha-music
   ```

2. **Launch the player**:
   - Double-click `index.html` to open it directly in your browser.
   - Or serve with a local development server for optimal Web Audio performance:
     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node npx serve
     npx serve .
     ```
   - Open `http://localhost:8000` in your browser.

---

## 🛠️ Built With

- **HTML5**: Semantic markup, custom audio elements, canvas visualizer.
- **CSS3**: Modern CSS custom properties (variables), Glassmorphism (`backdrop-filter`), Flexbox, CSS Grid, keyframe animations.
- **JavaScript (ES6+)**:
  - `AudioContext`, `AnalyserNode`, `BiquadFilterNode`, `DelayNode`, `GainNode`, `OscillatorNode`.
  - Canvas 2D Rendering Context for real-time visualizers.
  - HTML5 File API & Drag-and-Drop API.
  - Local state management and DOM manipulation.

---

## 👨‍💻 Developer & Internship

- **Developer**: [Devansh Yadav](https://github.com/Devansh-Yadav22)
- **Internship**: Web Development Internship at **CodeAlpha**
- **Repository**: [https://github.com/Devansh-Yadav22/codealpha-music](https://github.com/Devansh-Yadav22/codealpha-music)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
