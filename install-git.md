# Set Up Git

Here are instructions on how to set up Git (generated using GPT-4.1)

## Install

### For Windows

1.	**Download the Installer:**
   - Go to the [official Git website](https://git-scm.com/download/win) and the download will start automatically.

2.	**Run the Installer:**
   - Locate the downloaded .exe file and double-click to run it.
   - Follow the setup prompts. Default options are generally fine for most users.
   - On the “Adjusting your PATH environment” step, select **“Git from the command line and also from 3rd-party software.”**
   - On the “Configuring the line ending conversions” step, select **“Checkout Windows-style, commit Unix-style line endings.”**
3.	**Finish Installation:**
   - Click “Install” and let the process complete.
   - Click “Finish” to close the installer.

4.	**Verify Git Installation:** `git --version`
   - Run this command in **Command Prompt** or **Git Bash** to ensure Git is installed.

### For macOS

1.	**Install via Homebrew (recommended):**
   - If you have [Homebrew](https://brew.sh/) installed, open Terminal and run: `brew install git`
2.	**Or Download the Installer:**
   - Download the latest installer from [git-scm.com](https://git-scm.com/download/mac) and run the .dmg file.

3.	**Verify Git Installation:** `git --version`
   - Run this command in Terminal to check the installation.

### For Linux (Ubuntu/Debian)

1.	**Open a Terminal and Run:**
	
		sudo apt update
		sudo apt install git

2. **Verify Git Installation:** `git --version`

### For Linux (Fedora)

1.	**Open a Terminal and Run:** `sudo dnf install git`

2.	**Verify Git Installation:** `git --version`

## Configure

**After installation, you can configure your username and email:**

```
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```


That’s it! Git is now installed and ready for use on your system.