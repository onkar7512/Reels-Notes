# 🎬 Reel Notes – Social Video & Reels Note Saver

**Reel Notes** is a modern, lightweight Android app that lets you save videos and reels from **Instagram, YouTube Shorts, TikTok, Facebook, Twitter/X, and more** directly via Android's native share menu. 

Never lose track of why you saved a video—add a quick title, notes or recipe steps, and organize everything into customizable categories.

---

## ✨ Features

- 📲 **Direct System Share Integration**: Share directly from Instagram, YouTube, TikTok, or your browser without having to copy-paste links manually.
- 🎨 **Clean & Simplified UI**: Focuses on what matters:
  - **Video Link**
  - **Title**
  - **Description / Notes**
  - **Category Slider**
- 🖼️ **Video Thumbnails**: Displays video previews right on the front card for instant visual recognition.
- 🚀 **One-Tap Video Launch**: Tap **"Open Video"** to jump straight into the native app (Instagram, YouTube, etc.) or your browser.
- 📤 **Reel / Video Sharing**: Easily share saved video notes and links with friends or messaging apps.
- 🏷️ **Customizable Categories**: Add your own custom categories (e.g., *Cooking*, *Workout*, *Travel*, *Coding*) and delete ones you don't need.
- 🔍 **Instant Search & Category Filtering**: Find any saved reel by title, keyword, notes, or category.
- 💾 **100% Offline & Private**: Built with Room SQLite database—all your data stays locally on your device.

---

## 🛠️ Supported Platforms

- **Instagram** (Reels & Posts)
- **YouTube Shorts & Videos**
- **TikTok**
- **Twitter / X**
- **Facebook Reels & Watch**
- **Any web video URL**

---

## 📱 How It Works

1. While watching a Reel or Short on **Instagram**, **YouTube**, or **TikTok**, tap **Share** (✈️).
2. Select **Reel Notes** from the Android share sheet.
3. The app automatically detects the platform, cleans URL tracking tags, and opens the save sheet.
4. Add a title, write your notes or description, pick a category, and tap **Save**.
5. Browse your saved collection anytime with thumbnail previews and quick search!

---

## 🏗️ Tech Stack & Architecture

- **Language:** [Kotlin](https://kotlinlang.org/)
- **UI Toolkit:** [Jetpack Compose](https://developer.android.com/jetpack/compose) with [Material Design 3 (M3)](https://m3.material.io/)
- **Architecture:** MVVM (Model-View-ViewModel) + Repository Pattern
- **Local Persistence:** [Room Database](https://developer.android.com/training/data-storage/room) (SQLite) with Kotlin Coroutines & `Flow`
- **Image Loading:** [Coil](https://coil-kt.github.io/coil/) for Compose
- **Concurrency:** Kotlin Coroutines & `StateFlow`
- **Minimum SDK:** Android 7.0 (API Level 24)
- **Target SDK:** Android 15 / 16 (API Level 36)

---

## 🚀 Building & Running

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/reel-notes.git
