# Music-Ear-Trainer
Ear Trainer -Swar Abhyas

App link - https://prabhwho-cloud.github.io/Music-Ear-Trainer/EarTuner-SwarAbhyas.html

# Ear Trainer Swar Abhyas 

**Swar Abhyas** is a mobile-responsive, web-based ear training application designed for students and practitioners of Indian Classical Music. It helps users develop pitch recognition and ear training across all 12 swaras (Shudh, Komal, and Teevr) starting from any base pitch (Sa).

The app relies purely on the **Web Audio API** for tone generation—meaning zero audio files or external media assets are required, making it lightweight and fast to load.

---

## ✨ Features

* **Flexible Base Pitch (Sa):** Select base pitches ranging from low **G (196 Hz)** up to **F# (369.99 Hz)** to match your singing range or instrument tuning.
* **Two Practice Modes:**
  * **Shudh Only:** Focus on the 8 fundamental natural notes (*Sa, Re, Ga, Ma, Pa, Dha, Ni, Sa'*).
  * **Mixed Notes:** Challenge yourself with all 13 swaras, including **Komal** (*re, ga, dha, ni*) and **Teevr** (*Ma*) notes.
* **Synthesized Indian Sound Instruments:**
  * **Harmonium:** Rich dual-reed oscillator timbre with a soft detune.
  * **Bansuri:** Airy sine-wave flute tone with natural breath envelope and subtle vibrato.
  * **Piano:** Clean, percussive tone with organic decay.
* **Monophonic Audio Engine:** Automatically cuts off previous notes when a new button is tapped to prevent overlapping sound clutter.
* **3-Second Sustained Tones:** Gives ample listening time to evaluate and internalize pitches.
* **Gamified Feedback:**
  * Real-time accuracy tracking (**Score** and **Streak** counters).
  * Instant visual cues (green for correct, red for incorrect).
* **100% Mobile Ready:** Optimized touch interface designed for smartphones, tablets, and desktop browsers alike.

---

## 🛠️ Tech Stack

* **HTML5 & Vanilla JavaScript (ES6+)**
* **Tailwind CSS** (via CDN)
* **Web Audio API** (Custom Audio Synthesis)

