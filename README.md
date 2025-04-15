# vegetARian (2022) 🍆🥕🥬

**An interactive AR-based cooking game built with Processing and NyARToolkit, where players prepare virtual vegetables in real space using marker cards.**  
This playful experience combines object recognition, motion-based interaction, and sound feedback into a real-time augmented cooking game.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Development Stack](#development-stack)
- [Demo](#demo)
- [License](#license)

---

## 🥗 Overview

**vegetARian** is a marker-based AR cooking game developed with Processing.  
Players interact with real-world printed markers to "harvest" virtual vegetables and cook them using bullets symbolizing kitchen tools like pans, knives, and microwaves.  
The game combines real-time 3D object rendering, AR detection, sound effects, and interactive gameplay through keyboard and camera input.

---

## 🌟 Features

- 🔍 **AR Marker Tracking**: Uses NyARToolkit (`nyar4psg`) for marker detection
- 🥬 **Vegetable Recognition**: Players detect and collect the correct vegetables as shown in the recipe
- 🔫 **Cooking Phase with Bullets**: Type the correct key to activate cooking tools and process the ingredients
- 🎵 **Sound Feedback**: Audio changes by phase and includes success/failure effects
- 📸 **Camera Input**: Real-time AR using webcam with `processing.video` library
- 🕹️ **Mini-game Structure**: Includes harvest, instruction, cooking, and result phases

---

## ⚙️ Installation

1. Download and install [Processing](https://processing.org/)
2. Install the following libraries via the Processing Contribution Manager:
   - `NyAR4psg` (NyARToolkit for Processing)
   - `processing.video`
   - `processing.sound`
3. Clone or download this repository:
```bash
git clone https://github.com/kamekingdom/vegetARian.git
