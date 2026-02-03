[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://musicplaynest.vercel.app)          ![GitHub stars](https://img.shields.io/github/stars/TheHemantPandey/spotify-inspired-responsive-music-player?style=social)






# 🎵 MusicPlayNest – Spotify Inspired Responsive Music Player

MusicPlayNest is a Spotify-inspired, fully responsive web-based music player developed using **HTML, CSS, and Vanilla JavaScript**.  
The project dynamically detects music folders from the repository and automatically converts them into playlists, making it scalable and easy to manage.

🔗 **Live Demo:** https://musicplaynest.vercel.app  
🔗 **GitHub Repository:** https://github.com/TheHemantPandey/spotify-inspired-responsive-music-player/

---
## 📸 Screenshots

### Desktop View
![Desktop]<img width="1111" height="571" alt="image" src="https://github.com/user-attachments/assets/b8ff4155-0378-4736-831c-8f67640e148b" />

### Mobile View, Playlist View     and ofcourse Tablet View
<img width="884" height="422" alt="image" src="https://github.com/user-attachments/assets/99ae5fc8-25a9-4c8f-89be-ecfdbf9e0790" />









## 🚀 Features

- 🎧 Spotify-inspired clean UI
- 📁 Automatic playlist generation from folders
- 📱 Fully responsive (Desktop, Tablet, Mobile)
- ▶️ Play / Pause / Next / Previous controls
- 🎶 Dynamic song loading using JSON
- 🖼️ Album cover & song metadata support
- ⚡ Fast and lightweight (No frameworks)

---

## 🛠️ Tech Stack

- **HTML5** – Structure
- **CSS3** – Styling & responsive layouts
- **JavaScript (Vanilla)** – Logic & interactivity
- **JSON** – Song metadata handling
- **Vercel** – Deployment & hosting

---

## 📂 Project Folder Structure

```plaintext
public/
│
├── img/                     # UI images & icons
├── mediaqueries/            # Responsive CSS files
│   ├── meddesktopscreen.css
│   ├── tabletScreen.css
│   ├── medmobilescreen.css
│   └── minmobilescreen.css
│
├── songs/
│   ├── folder1/
│   │   ├── 7 Years - PagalWorld.mp3
│   │   ├── All Stars - PagalWorld.mp3
│   │   ├── Cheri - PagalWorld.mp3
│   │   ├── Die Smile - PagalWorld.mp3
│   │   ├── cover.jpeg
│   │   ├── info.json
│   │   └── songs.json
│   ├── folder2/
│   ├── ...
│   └── folder18/
│
├── index.html               # Main HTML file
├── index.css                # Main stylesheet
├── utility.css              # Utility classes
├── index.js                 # Core JavaScript logic
├── favicon.ico
│
├── package.json
└── package-lock.json

```

🔄 How Playlist System Works

Each folder inside /songs is treated as a playlist

songs.json contains track details for that playlist

info.json stores playlist metadata

JavaScript dynamically:

Detects folders

Loads song lists

Renders playlists automatically

✅ No hardcoded playlists
✅ Easy to scale by adding new folders

---

📱 Responsiveness

The UI is fully responsive using custom media query styles:

Desktop screens

Tablets

Medium mobile devices

Small mobile devices

All layouts are handled manually without frameworks.

---

🧠 What I Learned

JavaScript DOM manipulation

Audio API handling

Dynamic content rendering

Folder-based data architecture

Responsive UI design using CSS media queries

Hosting and deploying projects on Vercel

Managing large assets in GitHub repositories

---

🧪 How to Run Locally
git clone https://github.com/TheHemantPandey/spotify-inspired-responsive-music-player.git
cd spotify-inspired-responsive-music-player
open index.html


No additional setup required.
---

👤 Author

Hemant Pandey
B.Tech CSE Student
Aspiring Frontend / Web Developer

---
