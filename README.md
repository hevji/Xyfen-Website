# XYFEN 🎬

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/platform-Windows%20|%20Mac%20|%20Linux-lightgrey.svg)]()

---

Welcome to **XYFEN** – your **fast, ad-free, and completely local video downloader** powered by `yt-dlp`. XYFEN makes downloading videos from various platforms simple, efficient, and completely **user-friendly**. No ads, no online trackers, just pure functionality.  

---

## 🌟 Key Features

| Feature | Description |
|---------|-------------|
| **Ad-Free** | No annoying pop-ups or advertisements. Just pure downloads. |
| **Completely Local** | All downloads and operations happen on your device. Your data stays private. |
| **User-Friendly GUI** | Intuitive interface with tabs for Downloading, Finished, History, and Failed videos. |
| **Multiple Download Engines** | Uses `aria2` for fast, segmented downloads; falls back to `yt-dlp` if needed. |
| **Format & Quality Selection** | Choose video/audio formats and resolutions before downloading. |
| **Cross-Platform** | Works on Windows, Mac, and Linux. |
| **History & Resume** | Keep track of downloads and resume interrupted tasks. |
| **Open Source** | Fully open-source. Extendable and customizable. |

---

## 📊 XYFEN vs Other Downloaders

| Feature | XYFEN | 4K Video Downloader | ClipGrab | YTD |
|---------|-------|------------------|---------|-----|
| Ad-Free | ✅ | ❌ | ✅ | ❌ |
| Local-Only | ✅ | ❌ | ✅ | ❌ |
| Uses `yt-dlp` | ✅ | ❌ | ❌ | ❌ |
| Multi-Threaded Downloads | ✅ | ✅ | ❌ | ❌ |
| Format Selection | ✅ | ✅ | ✅ | ❌ |
| Open Source | ✅ | ❌ | ✅ | ❌ |
| User-Friendly GUI | ✅ | ✅ | ✅ | ✅ |

> XYFEN focuses on **privacy, speed, and simplicity**, while other apps often include ads, trackers, or unnecessary complexity.

---

## ⚡ How It Works

XYFEN primarily uses **`aria2`** for fast segmented downloads. If `aria2` is not available or fails, it automatically falls back to **`yt-dlp`**. You can also manually choose to use `yt-dlp` only.

1. Paste a video URL into the download field.
2. Choose your desired format and quality.
3. Click **Download**.
4. Track progress in the **Downloading** tab.
5. Completed downloads appear in **Finished**. Failed downloads appear in **Failed**.

---

## 🛠 Installation

**Requirements:**
- Python 3.10+
- `yt-dlp` installed (can be bundled)
- Optional: `aria2` for faster downloads

**Clone & Setup:**

```bash
git clone https://github.com/yourusername/xyfen.git
cd xyfen
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python main.py
```
## 🔑 Key Points

- Privacy-Focused: No analytics, no online tracking, everything stays on your device.

- Fully Local: No need for a server or cloud; you control all downloads.

- Simple GUI: Tabs make it easy to organize downloads, check history, or retry failed tasks.

- Fast & Reliable: aria2 integration allows multi-threaded downloads for max speed.

- Customizable: Open-source, so you can tweak or extend features.


## 🏆 Why XYFEN?

- No Ads: Purely for downloading videos without interruptions.

- Local & Private: Everything runs on your computer.

- Open Source: 100% free, extendable, and community-driven.

- User-Friendly: Minimalist design, organized tabs, and instant downloads.

## 📜 License

- This project is licensed under the **`MIT License`** - see the LICENSE
 file for details.

## 💬 Support

For questions, issues, or feature requests, open an issue on GitHub or join the XYFEN Discord
.

⚡ Quick Links

- [GitHub Repository](https://github.com/hevji/xyfen)

- Installation Instructions (coming soon)

- [Licence](https://xyfen.lovable.app/licence.txt)

> XYFEN – download videos your way. Fast, local, and ad-free.
