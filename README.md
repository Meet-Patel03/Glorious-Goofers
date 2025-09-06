# 🚀 FocusFlow

**Your intelligent companion for conquering digital distractions and mastering your focus.**  

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/downloads/) 
![Status](https://img.shields.io/badge/status-active-success.svg)

---

## 🌟 Overview
FocusFlow is a **real-time productivity tracker** that monitors your screentime across all applications, classifies your activity as **Productive, Neutral, or Non-Productive**, and provides **intelligent reminders and warnings** to keep you on track.  

At the end of each focus session, FocusFlow generates a **session summary report** — showing how much of your time was spent productively, along with detailed percentages.  

Whether you’re a student, developer, or professional — FocusFlow helps you stay in control of your digital habits and maximize your deep work sessions.

---

## ✨ Key Features
- ⏱ **Live Screentime Tracking** → Monitors active windows in real time.  
- 🏷 **Smart Classification** → Categorizes activity into *Productive*, *Neutral*, and *Non-Productive* based on customizable keywords.  
- 🔔 **Focus Session Reminders** → Sends subtle reminders during focus sessions to keep you engaged.  
- ⚠️ **Distraction Warnings** → Alerts you instantly when you spend too long on non-productive apps.  
- 📊 **Session Summary Reports** → End-of-session breakdown with:  
  - Total time spent in each category.  
  - Productivity percentage.  
  - Clear session insights to help you improve.  
- 💻 **Cross-Platform** → Works on **Windows** and **Linux** with dedicated executables, or run directly from source code.  
- ⚙️ **Fully Customizable** → Edit `config.json` to define what counts as productive or distracting.  

---

## 📸 Demo
*A quick look at FocusFlow in action.*  
> **Suggestion:** Add screenshots or a GIF of your app here.  

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Demo](#-demo)
- [Installation & Usage](#-installation--usage)
  - [For Regular Users](#for-regular-users)
  - [For Developers](#for-developers)
- [Configuration](#-configuration)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🚀 Installation & Usage

### ✅ For Regular Users (No Setup Required)
Download and run the **pre-compiled executables**:
1. Go to the **[Releases](https://github.com/your-username/FocusFlow/releases)** page.  
2. Download the latest version for your OS:  
   - `FocusFlow-Windows.exe` (Windows)  
   - `FocusFlow-Linux` (Linux)  
3. Double-click the file to start tracking your productivity.  

---

### 👩‍💻 For Developers
Run FocusFlow directly from source code:

```bash
# Clone the repository
git clone https://github.com/your-username/FocusFlow.git
cd FocusFlow

# Create and activate a virtual environment
# Windows
python -m venv venv
.\venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python main.py
