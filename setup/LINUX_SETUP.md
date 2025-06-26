# Linux Setup Guide 🐧

This guide will help you set up all required tools for the MI-AIR 2025 Conference materials on Linux.

## Install Git
- Open Terminal. 💬
- Run:
  ```
  sudo apt-get update
  sudo apt-get install git
  ```

## Install Ollama
  ```
  curl -fsSL https://ollama.com/install.sh | sh
  ```

## Install LM Studio
- Download the latest `.deb` or `.AppImage` from [LM Studio Downloads](https://lmstudio.ai/download) and follow the instructions for your distribution.

## Install VSCode (Part 3 Only)
- For Debian/Ubuntu:
  ```
  sudo apt update
  sudo apt install wget gpg
  wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
  sudo install -o root -g root -m 644 packages.microsoft.gpg /usr/share/keyrings/
  sudo sh -c 'echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" > /etc/apt/sources.list.d/vscode.list'
  sudo apt update
  sudo apt install code
  ```
- Or download the `.deb` or `.rpm` from [VSCode Downloads](https://code.visualstudio.com/Download).

## Download the Repository
- Open your terminal. 💻
- Choose a folder where you want to save the files (e.g., your Desktop):
  ```
  cd ~/Desktop
  ```
- Copy and paste the following command and press Enter:
  ```
  git clone https://github.com/tastslikchkn/MI-AIR-2025.git
  ```

## Open the Files
- Navigate to the downloaded folder and open the `.md` files with any text editor (Gedit, VSCode, etc.). 📝
