# Setup for Coding with Agentic AI Workshop

## Software Requirements

### 1. Node.js and NPM
- **Required Version:** Node.js 18+ and npm 9+
- **Installation:**
  - Download Node.js from [nodejs.org](https://nodejs.org) *(npm comes bundled with Node.js)*
  - Or use nvm (Node Version Manager):
    - **Windows:**
      - `winget install CoreyButler.NVMforWindows`
      - `nvm install latest`
      - `nvm use latest`
    - **Unix/macOS:**
      - `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash`
      - `nvm install node`  *(installs latest version)*
- **Verify Installation:**
  - `node --version`  *(Should show v18+)*  
  - `npm --version`   *(Should show v9+)*
- **Update npm (if needed):**
  - `npm install -g npm@latest`

### 2. Git
- **Required Version:** 2.x+
- **Installation:**
  - **Windows:** Download from [git-scm.com](https://git-scm.com)
  - **macOS:** `brew install git`
  - **Linux:** `sudo apt-get install git`
- **Verify Installation:**
  - `git --version`
- **Initial Setup:**
  - `git config --global user.name "Your Name"`
  - `git config --global user.email "your.email@example.com"`

### 3. VS Code Insiders
- **Purpose:** Enhanced development experience with the latest features
- **Installation:**
  - Download from [code.visualstudio.com/insiders](https://code.visualstudio.com/insiders)
  - Or through winget: `winget install Microsoft.VisualStudioCode.Insiders`
- **Verify Installation:**
  - The Command Palette should show **Code - Insiders**
  - Or check via: `code-insiders --version`

### 4. GitHub CLI (gh)
- **Required Version:** Latest
- **Installation:**
  - **Windows:** `winget install GitHub.cli`
  - **macOS:** `brew install gh`
  - **Linux:** `sudo apt install gh`
- **Verify Installation:**
  - `gh --version`
- **Authentication:**
  - Run `gh auth login` and follow the prompts to authenticate with GitHub

### 5. Docker Desktop
- **Required Version:** Latest
- **Installation:**
  - Download from [docker.com](https://www.docker.com)
  - Or through winget: `winget install Docker.DockerDesktop`
- **Verify Installation:**
  - `docker --version`
  - `docker-compose --version`

### 6. NPX
- **Description:** Bundled with npm 5.2+; executes packages without installing them globally
- **Verify Installation:**
  - `npx --version`
- **Update (via npm):**
  - `npm install -g npm@latest`  *(This also updates npx)*

### 7. VS Code Extension for GitHub Copilot
- **Installation:**
  - Install **VS Code Insiders** from [code.visualstudio.com/insiders](https://code.visualstudio.com/insiders)  
    **Note:** If you already have VS Code installed, it is recommended to uninstall it fully before installing VS Code Insiders.
- **Setup:**
  - Upon launch, the home screen will prompt you to install GitHub Copilot.
  - Click the **Setup Copilot** button in the center.
  - A GitHub login screen will appear; log in with your GitHub credentials.
  - After authentication, VS Code Insiders will display the GitHub Copilot interface.
- **Agent Mode Configuration:**
  - In the GitHub Copilot pane, locate the **Copilot Edit** icon on the top right.
  - Change the drop-down (located to the left of "GPT4o") from **Edit** to **Agent**.
  - With Agent Mode enabled, you can now give commands to take actions on your behalf. 
 
