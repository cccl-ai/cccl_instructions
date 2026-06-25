---
layout: default
title: "CCCL LON #9 — Attendee Instructions"
description: "Everything you need to know before CCCL London #9."
event_date: "Monday 29 June 2026"
subtitle: "Follow the instructions for installing prerequisites for the event"
---

## Prerequisites

Please complete the following setup **before** the event. If you run into issues, join the WhatsApp group and ask for help.

---

<details class="step-collapsible" markdown="1">
<summary class="step-summary">Step 1. Install Git &amp; GitHub</summary>

### Mac

1. Open **Terminal** (search "Terminal" in Apps).
2. Run: `git --version`
   - If Git is not installed, macOS will prompt you to install Xcode Command Line Tools. Click **Install** and wait for it to complete.
3. Create a free account at [github.com](https://github.com) if you don't have one.
4. Configure Git with your name and email:
   ```bash
   git config --global user.name "Your Name"
   ```
   ```bash
   git config --global user.email "you@example.com"
   ```

### Windows

1. Download **Git for Windows** from [git-scm.com/download/win](https://git-scm.com/download/win).
2. Run the installer — accept the defaults (make sure "Git Bash Here" is checked).
3. Open **Git Bash** (right-click on the desktop or search in Start).
4. Create a free account at [github.com](https://github.com) if you don't have one.
5. Configure Git:
   ```bash
   git config --global user.name "Your Name"
   ```
   ```bash
   git config --global user.email "you@example.com"
   ```

</details>

---

<details class="step-collapsible" markdown="1">
<summary class="step-summary">Step 2. Install Claude CLI (Claude Code)</summary>

### Mac

1. Make sure **Node.js 18+** is installed. Check with:
   ```bash
   node --version
   ```
   If not installed, download it from [nodejs.org](https://nodejs.org).
2. Install Claude Code globally:
   ```bash
   npm install -g @anthropic-ai/claude-code
   ```
3. Verify the install:
   ```bash
   claude --version
   ```
4. On first run, `claude` will open a browser tab to authenticate with your Anthropic account.

### Windows

1. Make sure **Node.js 18+** is installed. Download from [nodejs.org](https://nodejs.org) and run the installer.
2. Open **Command Prompt** or **PowerShell** and install Claude Code:
   ```bash
   npm install -g @anthropic-ai/claude-code
   ```
3. Verify the install:
   ```bash
   claude --version
   ```
4. On first run, `claude` will open a browser tab to authenticate with your Anthropic account.

> **Note (Windows):** If you see a permissions error, run PowerShell as Administrator and retry.

</details>

---

<details class="step-collapsible" markdown="1">
<summary class="step-summary">Step 3. Install VS Code with Python</summary>

### Mac

1. Download **Visual Studio Code** from [code.visualstudio.com](https://code.visualstudio.com).
2. Open the `.dmg` file and drag VS Code to your **Applications** folder.
3. Open VS Code. Press `Cmd+Shift+X` to open Extensions.

### Windows

1. Download **Visual Studio Code** from [code.visualstudio.com](https://code.visualstudio.com).
2. Run the installer — check **"Add to PATH"** during setup.
3. Open VS Code. Press `Ctrl+Shift+X` to open Extensions.

</details>

---

<details class="step-collapsible" markdown="1">
<summary class="step-summary">Step 4. Kata Repo &gt; <strong>Good to have</strong></summary>

Get the kata repository before the event so you're ready to code straight away:

```bash
git clone https://github.com/cccl-ai/cccl-kata-workshop.git
```

</details>

---

<details class="step-collapsible" markdown="1">
<summary class="step-summary">Step 5. Join the WhatsApp Group</summary>

Stay updated and get help from other attendees before and during the event:

[Join the CCCL - KATA Workshop WhatsApp group](https://chat.whatsapp.com/DQuzeeKobHlC4zbKLVaLfZ?s=sh&p=a&ilr=4)

</details>

--- 

## Need Help?

Drop a message in the WhatsApp group. See you on **29 June 2026**!
