# ☁️ SoundScript CDN

**SoundScript CDN** is the dedicated media distribution layer for the SoundScript music platform.

It stores and serves all **albums, audio tracks, cover art, artist images, and metadata JSON** required by the SoundScript web app.

This repository acts as a **public content delivery backend**, allowing the main app to remain lightweight, fast, and GitHub-safe.

---

## 🧱 Purpose

This repository exists to:

• host all music & image assets
• store album metadata in structured JSON
• provide stable public URLs
• prevent the main app repo from exceeding GitHub size limits
• enable unlimited album expansion

It contains **no application logic** — only distributable media content.

---

## 📁 Clickable Repository Structure

[soundscript-cdn/](/)  
├── [📁 artists/](/artists)  
│   ├── [info.json](/artists/info.json)  
│   └── [📁 images/](/artists/images)  
│  
├── [📁 songs/](/songs)  
│   ├── [default.svg](/songs/default.svg)  
│   ├── [info.json](/songs/info.json)  
│   ├── [README.md](/songs/README.md)  
│   │  
│   ├── [📁 chill-nights/](/songs/chill-nights)  
│   │   ├── [info.json](/songs/chill-nights/info.json)  
│   │   ├── [0.mp3](/songs/chill-nights/0.mp3)  
│   │   ├── [1.mp3](/songs/chill-nights/1.mp3)  
│   │   ├── [2.mp3](/songs/chill-nights/2.mp3)  
│   │   ├── [3.mp3](/songs/chill-nights/3.mp3)  
│   │   ├── [4.mp3](/songs/chill-nights/4.mp3)  
│   │   ├── [5.mp3](/songs/chill-nights/5.mp3)  
│   │   ├── [6.mp3](/songs/chill-nights/6.mp3)  
│   │   └── [📁 covers/](/songs/chill-nights/covers)  
│   │  
│   ├── [📁 gaming/](/songs/gaming)  
│   ├── [📁 mood-refresher/](/songs/mood-refresher)  
│   ├── [📁 soft-phonk/](/songs/soft-phonk)  
│   └── [📁 study-and-workout/](/songs/study-and-workout)  
│  
├── [🕒 CHANGELOG.md](/CHANGELOG.md)  
└── [📄 README.md](/README.md)

---

## ⚡ CDN Usage

The SoundScript web app loads all music and metadata from this repository via direct public URLs.

Local development mirrors the same folder layout.
Only the **base path** changes.

---

## 📦 Contents

* MP3 music tracks
* Album covers (JPG / PNG)
* Artist images
* Album metadata (`info.json`)
* Global default artwork

No code, no scripts, no tracking.

---

## 📈 Scalability

This repo is designed to grow:

• unlimited albums
• version-safe metadata
• no impact on app size
• clean Git history

---

## 🔐 License

All media belongs to their respective owners.
This repository is intended strictly for educational / personal demo use.
