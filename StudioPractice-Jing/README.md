This is an example folder structure and template set for MA MFA Goldsmiths Computational Arts studio practice students.
This folder structure is intended to be used with Obsidian, and is therefore written in markdown.

 Follow the steps below to get your own copy, download it to your computer, and open it in Obsidian.



## Before you start

You'll need:

- A free [GitHub account](https://github.com/signup)
- [Obsidian](https://obsidian.md/download) installed
- Either **Git** (for the command line) or **[GitHub Desktop](https://desktop.github.com/)**


## 1. Fork the repository

Forking creates your own copy of the vault on GitHub, so you can save changes without affecting the original.

1. Sign in to GitHub and open this repository's page.
2. Click **Fork** (top right).
3. Leave the defaults as they are and click **Create fork**.

You now have a copy at `https://github.com/YOUR-USERNAME/StudioPracticeExampleVault`.


## 2. Download (clone) your fork

Pick **one** of the two options below.

### Option A: Command line

1. Open a terminal (Terminal on macOS/Linux, PowerShell or Git Bash on Windows).
2. Move to the folder where you want the vault to live, for example:
   ```bash
   cd ~/Documents
   ```
3. Clone your fork (replace the placeholders with your details):
   ```bash
   git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
   ```
4. A new folder called `REPO-NAME` now contains the vault.

To save and upload your changes later:
```bash
cd REPO-NAME
git add .
git commit -m "Describe your changes"
git push
```

### Option B: GitHub Desktop

1. Open GitHub Desktop and sign in with your GitHub account (**File → Options → Accounts** on Windows, **GitHub Desktop → Settings → Accounts** on macOS).
2. Go to **File → Clone repository**.
3. On the **GitHub.com** tab, select `YOUR-USERNAME/REPO-NAME` from the list.
4. Choose a **Local path** (e.g. your Documents folder) and click **Clone**.

To save and upload your changes later: write a summary in the bottom-left box, click **Commit to main**, then click **Push origin**.


## 3. Open the vault in Obsidian

1. Open Obsidian.
2. On the start screen, choose **Open folder as vault** (if a vault is already open, click the vault switcher in the bottom-left and choose **Manage vaults**).
3. Select the `REPO-NAME` folder you just cloned and click **Open**.
4. If the vault includes community plugins, Obsidian will ask whether you trust the author. Choose **Trust author and enable plugins** only if you're happy to run them. NB this version does not include community plugins.

That's it — the example vault is ready to explore!

## Tips

- **Keep your copy up to date with the original:** on your fork's GitHub page, click **Sync fork → Update branch**, then pull the changes (`git pull` on the command line, or **Fetch origin → Pull origin** in GitHub Desktop).
- **Workspace noise:** Obsidian constantly updates `.obsidian/workspace.json`. Adding it to `.gitignore` keeps your commits clean.
