<img src="../images/windows.png" alt="Windows" width="50" style="vertical-align:middle;"/></a> Windows Setup Guide

This guide will help you set up all required tools for the MI-AIR 2025 Conference materials on Windows.

## Install Git Bash or Git
- Open Command Prompt (search for `cmd` in the Start menu). 💬
- Right-click on 'Command Prompt' and select **Run as administrator**. (This is required for some installations.)
- Run:
  ```
  winget install --id Git.Git -e --source winget
  ```
- Or, download and install manually from [Git for Windows](https://git-scm.com/download/win). 🖱️

## Install Ollama
  ```
  winget install Ollama.Ollama
  ```

## Install LM Studio
- Download the latest Windows installer from [LM Studio Downloads](https://lmstudio.ai/download) and run the installer.

## Install VSCode (Part 3 Only)
- **Run all the following commands in Command Prompt as administrator:**
  ```
  winget install Microsoft.VisualStudioCode
  ```

## Download the Repository
- Open your terminal (Git Bash, Command Prompt, or Terminal). 💻
- Choose a folder where you want to save the files (e.g., your Desktop):
  ```
  cd ~/Desktop
  ```
- Copy and paste the following command and press Enter:
  ```
  git clone https://github.com/tastslikchkn/MI-AIR-2025.git
  ```

## Open the Files
- Navigate to the downloaded folder and open the `.md` files with any text editor (Notepad, WordPad, VSCode, etc.). 📝
