# 🎵 Kannadi Poove - Lyrical Song Player ✨

<div align="center">

[![Instagram](https://img.shields.io/badge/Instagram-%40K4issz.luv-E4405F?style=flat-square&logo=instagram)](https://instagram.com/K4issz.luv)
[![Python](https://img.shields.io/badge/Python-3.7+-3776ab?style=flat-square&logo=python)](https://www.python.org/)
[![GitHub](https://img.shields.io/badge/GitHub-K4isszDev-181717?style=flat-square&logo=github)](https://github.com/K4isszDev/kannadi-poove-lyrics)

> ✨ Character-by-character animated lyrics with synchronized audio playback

### 🎬 [Watch Live Demo](https://www.instagram.com/reel/DQ1569niAbI/) • 🎵 [Listen on Spotify](https://open.spotify.com/track/3MELuNUntwMZwsNK9zNxJi)

</div>

---

## 📖 About

A Python lyrical song player that displays lyrics with smooth animation and synchronized audio. Fully customizable—change lyrics, timing, and songs to create your own experiences!

**⚠️ Disclaimer:** This is a fan-made project. I do not own the original song. All rights belong to composer **Santhosh Narayanan**. Created for educational and entertainment purposes only.

---

## 🎼 Song Details

| Attribute | Information |
|-----------|-------------|
| **Title** | Kannadi Poove |
| **Artist** | Santhosh Narayanan |
| **Language** | Tamil |
| **Genre** | Romantic Drama |

---

## ✨ Features

- ⌨️ **Character-by-Character Animation** - Smooth typewriter effect
- 🔊 **Synchronized Audio** - Music plays with lyrics using pygame
- ⏱️ **Customizable Timing** - Adjust speed and gaps for perfect sync
- 🎨 **Clean Display** - Professional terminal output
- 🛠️ **Easy Customization** - Change lyrics, timing, and audio files
- 🎵 **Universal Support** - Works with any MP3 file and lyrics

---

## 🚀 Quick Start

### 1️⃣ Installation

Clone and install dependencies:

```bash
git clone https://github.com/K4isszDev/kannadi-poove-lyrics.git
cd kannadi-poove-lyrics
pip install -r requirements.txt
```

### 2️⃣ Add Your Audio File

Place your MP3 file in the project folder and update the path in `main.py`:

```python
pygame.mixer.music.load("kannadi_poove.mp3")
```

### 3️⃣ Run It!

```bash
python main.py
```

---

## 🎨 Customization

### Edit Lyrics & Timing

Open `main.py` and modify the `lyrics` dictionary:

```python
lyrics = {
    0: {'text': "Your lyrics here", 'speed': 0.07, 'gap_after': 1.5},
    1: {'text': "Next line", 'speed': 0.07, 'gap_after': 1.0},
}
```

**Parameters:**
- 📝 `text` - The lyric line
- ⚡ `speed` - Delay per character (0.07 = standard, lower = faster)
- ⏸️ `gap_after` - Pause after line (None = no pause)

### Change Audio File

```python
pygame.mixer.music.load("path/to/your/song.mp3")
```

---

## 🔧 Troubleshooting

| Issue | Solution |
|-------|----------|
| 🔴 Audio file not found | Check file path in `main.py` matches your location |
| 🔴 pygame not installed | Run `pip install pygame` |
| 🔴 No sound output | Check system volume and MP3 file validity |
| 🔴 Timing mismatch | Adjust `speed` and `gap_after` values (0.01 increments) |

---

## 📁 Project Structure

```kannadi-poove-lyrics/
├── main.py              # 🐍 Main script
├── kannadi_poove.mp3    # 🎵 Audio file (add your own)
├── requirements.txt     # 📋 Dependencies
└── README.md            # 📖 Documentation
```

---

## 🎯 Perfect For

🎬 Music videos • 📱 Social media reels • ✨ Creative projects • 🐍 Learning Python • 💕 Fan projects

---

## ⚖️ License & Disclaimer

**Educational & Personal Use Only**

- 🚫 Not affiliated with original song creators
- ©️ All rights to "Kannadi Poove" belong to Santhosh Narayanan
- 💡 Fan-made project for entertainment only
- 🎵 You do not own the original song - please support the original artist

---

## 🤝 Connect & Support

- ⭐ Star this repository
- 📸 Follow [@K4issz.luv](https://instagram.com/K4issz.luv)
- 🎬 [Watch Demo](https://www.instagram.com/reel/DQ1569niAbI/)
- 🔀 Contribute via pull requests

---

<div align="center">

### 💙 Made with ❤️ by @K4isszDev

✨ *"Because some songs deserve more than just listening..."* ✨

</div>
