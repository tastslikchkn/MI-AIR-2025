<p align="center">
  <img src="logo_IA.jpg" alt="Conference Logo" width="1000"/>
</p>

<p align="center">
  <a href="https://sites.google.com/miair.org/miair2023/home">
    <img src="https://lh6.googleusercontent.com/VuND54NjC7Z3bU7bZUDFnIU4Fqi033z4YpPcYUcLeZI2tlWxG4DnAGt9IrNr9RVOOHM6rSFi1dWy_eBhDWDNPVGSbTV2Gcre_D2rV7ODgIGAfph73xsahhA2hnPhn0CW4IZK2zq9JX3OIhfYXOtuBt38nz-7O4Qd9q46OXvTnhuONFK8RqLDmg=w1280" alt="MI/AIR Conference Logo" width="300"/>
  </a>
</p>

[Visit the MI/AIR 2025 Conference Website](https://sites.google.com/miair.org/miair2023/home)

This repo contains abstracts, vocabulary guides, and supporting materials for the 3 part Local LLM series from the University of Michigan - Flint. Below is an overview of repository contents and directions on how to obtain and use the materials.

## Quick Start 🚀

1. **Browse Abstracts:**
   - View `abstracts.md` for a fun, readable version of all session abstracts. 📄

2. **Understand the Jargon:**
   - Learn about Ollama and LM Studio with dedicated vocabulary and links in the vocabulary file. 🤖
   - Check `vocabulary_and_acronyms.md` for definitions, coder examples, and analogies for better understanding. 💡
  

## How to Download This Repo 🖥️

### Install Git Bash or Git from the Command Line (Part 1,2,3) 🐙

#### Windows 🪟
- **Run all the following commands in Command Prompt as administrator:**
  - Search for `cmd` in the Start menu, right-click on 'Command Prompt', and select **Run as administrator**. (This is required for some installations.)
- Run:
  ```
  winget install --id Git.Git -e --source winget
  ```
- Or, download and install manually from [Git for Windows](https://git-scm.com/download/win). 🖱️

#### Mac 🍏
- Open Terminal (search for Terminal in Spotlight). 💬
- If you don't have Homebrew, install it first by running:
  ```
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
- Then, install Git:
  ```
  brew install git
  ```
- Learn more at [brew.sh](https://brew.sh/) 🛠️

#### Linux 🐧
- Open Terminal. 💬
- Run:
  ```
  sudo apt-get update
  sudo apt-get install git
  ```

### Download the Repository 📥
- Open your terminal (Git Bash, Command Prompt, or Terminal). 💻
- Choose a folder where you want to save the files (e.g., your Desktop):
  ```
  cd ~/Desktop
  ```
- Copy and paste the following command and press Enter:
  ```
  git clone <REPO_URL>
  ```
- Replace `<REPO_URL>` with the actual URL of this repository (e.g., from GitHub). 🔗

### Open the Files 📂
- Navigate to the downloaded folder and open the `.md` files with any text editor (Notepad, WordPad, VSCode, etc.). 📝

## Install Ollama and LM Studio from the Command Line (Part 1,2,3) 🛠️

### Windows 🪟
- **Run all the following commands in Command Prompt as administrator:**
  - Search for `cmd` in the Start menu, right-click on 'Command Prompt', and select **Run as administrator**. (This is required for some installations.)
- **Ollama:**
  ```
  winget install Ollama.Ollama
  ```
- **LM Studio:**
  ```
  winget install LMStudio.LMStudio
  ```

### Mac 🍏
- **Ollama:**
  ```
  brew install --cask ollama
  ```
- **LM Studio:**
  ```
  brew install --cask lm-studio
  ```

### Linux 🐧
- **Ollama:**
  ```
  curl -fsSL https://ollama.com/install.sh | sh
  ```
- **LM Studio:**
  - Download the latest `.deb` or `.AppImage` from [LM Studio Downloads](https://lmstudio.ai/download) and follow the instructions for your distribution.

---

## Install VSCode (Part 3 Only) 💻

### Windows 🪟
- **Run all the following commands in Command Prompt as administrator:**
  - Search for `cmd` in the Start menu, right-click on 'Command Prompt', and select **Run as administrator**. (This is required for some installations.)
  ```
  winget install Microsoft.VisualStudioCode
  ```

### Mac 🍏
  ```
  brew install --cask visual-studio-code
  ```

### Linux 🐧
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

## Useful Links 🔗

- [MI/AIR 2025 Conference Website](https://sites.google.com/miair.org/miair2023/home)
- [Ollama Documentation](https://github.com/ollama/ollama/tree/main/docs)
- [LM Studio Documentation](https://lmstudio.ai/docs/app)

## Contributing 🤝

Contributions and suggestions are welcome! Please open an issue or pull request if you have improvements or additional resources to share.

## License 📜

This repository is for educational and informational purposes for MI/AIR 2025 participants.

---

🎉 Enjoy the conference and happy learning! 🎉
