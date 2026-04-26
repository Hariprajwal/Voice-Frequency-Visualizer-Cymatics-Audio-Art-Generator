# Voice-Frequency-Visualizer-Cymatics-Audio-Art-Generator
VoiceFreqArt transforms your voice into mesmerizing visual patterns using real-time frequency analysis and cymatics-inspired rendering. Built with the Web Audio API and HTML5 Canvas, it detects your voice’s dominant frequency, range, and unique harmonic signature, then generates vibrant, physics-based visuals that react dynamically to sound.


<img width="1920" height="943" alt="upload" src="https://github.com/user-attachments/assets/04e8530f-49fc-4b1f-8eff-c95eb26ed543" />
<img width="1902" height="920" alt="image" src="https://github.com/user-attachments/assets/ddc3bee1-09e9-464c-bbfb-62ab902d1e46" />
<img width="419" height="312" alt="image" src="https://github.com/user-attachments/assets/240d169a-6069-4817-899a-ed0061a12639" />

# 🧬 Voice Frequency Visualizer: Digital Cymatics

**Voice Frequency Visualizer** is a generative art tool that explores the physics of sound through digital simulation. By analyzing voice or audio frequencies in real-time, the engine generates complex geometric patterns—mirroring the real-world phenomenon of **Cymatics** (the study of visible sound and vibration).

## 🚀 The Vision
To bridge the gap between auditory experience and visual geometry. This tool allows users to "see" their voice, mapping specific frequencies to intricate mathematical shapes.

## ✨ Key Features
* **Real-time Signal Analysis:** Uses Fast Fourier Transform (FFT) to process audio input with zero latency.
* **Cymatic Pattern Generation:** Generates nodal patterns based on frequency intensity.
* **Dynamic Color Mapping:** High-frequency tones map to vibrant spectra, while low-end frequencies create deep, pulsing structures.
* **Exportable Art:** Capture high-resolution frames of your unique voice patterns.

## 🛠 Tech Stack
* **Language:** Python 3.12
* **Audio Processing:** PyAudio / Librosa
* **Graphics Engine:** Pygame / OpenGL / Matplotlib
* **Math:** NumPy (for complex signal processing)

## 📦 How to Run
1. Calibrate your microphone.
2. Run the visualizer:
   ```bash
   python main.py --mode cymatic
