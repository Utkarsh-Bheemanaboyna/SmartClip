# 🎬 SmartClip AI — Automated Podcast Clipper

SmartClip AI is a modern SaaS platform designed to turn long-form podcasts into viral short clips optimized for YouTube Shorts, TikTok, and Instagram Reels. Using advanced AI models, it automatically detects engaging moments, adds stylized subtitles, and crops the video to focus on the active speaker.

---

## ✨ Features

* **🧠 Smart Moment Detection:** Identifies engaging segments, stories, and questions using Gemini 2.5 Pro.
* **🎯 Active Speaker Tracking:** Uses deep learning (`LR-ASD`) to keep the active speaker centered in vertical video format.
* **📝 Automatic Subtitles:** Generates fast, accurate transcriptions and animated subtitles via WhisperX.
* **⚡ High-Performance Rendering:** GPU-accelerated video rendering powered by `FFMPEGCV` and Modal serverless functions.
* **💳 Credit & Subscription System:** Built-in Stripe integration for credit packages.
* **📊 Background Processing:** Queue management using Inngest for scalable async task handling.

---

## 🛠️ Tech Stack

* **Frontend:** Next.js 15, React, TypeScript, Tailwind CSS, Shadcn UI, Auth.js
* **Backend API:** Python, FastAPI
* **AI & Processing:** WhisperX, LR-ASD, Gemini 2.5 Pro, FFMPEGCV
* **Infrastructure:** Modal (Serverless GPU), AWS S3, Inngest

---

## 🚀 Getting Started

### Prerequisites

* Python 3.12+
* Node.js 18+
* An AWS S3 bucket
* Modal & Inngest accounts

### 1. Clone the Repository

```bash
git clone --recurse-submodules [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
cd YOUR_REPO_NAME
