# Growth-Marketing-Project - Portfolio Setup

## Tools I Installed

- **Cursor IDE:** Downloaded from [cursor.com](http://cursor.com)
- **Claude Code extension:** Added via Cursor Extensions
- **Codex extension:** Added via Cursor Extensions
- **Git:** Downloaded from https://git-scm.com/

## Steps I completed
- Installed Cursor IDE: Installed on Windows.
- Added Claude Code Extension: Found via Cursor extensions panel inside primary bar, installed, not authenticated. I couldn't log in to it due to paid version.
- Added Codex Extension: Found via Cursor extension panel, installed, and authenticated.
- Created a GitHub account: Signed up at github.com with a personal email.
- Create a GitHub repository: Created and named it "Growth-Marketing-Project". Set up visibility to public with the <README.md> file and watched a YouTube tutorial for license selection. Selected MIT (it's best for modification, distribution, and commercial use.)
- Connected Git to cursor through browser login for better understanding.
- Installed Git: Download Git (Latest version: 2.54.0) for Windows from https://git-scm.com/. Watched a YouTube tutorial for the proper installation of it and for using cursor as a code editor.
- Cloned Git repository: Cloned Git Repo into cursor's command pallete inside view option. Used <git clone> in the terminal to pull the repo locally. Watched the same tutorial as Git installation.
- Configured Git credentials: Set up username and email using <git config --global>.
- Opened the cloned folder in Cursor.
- Wrote whole <README.md> File.
- Committed and pushed it to GitHub: Did it via the source control panel in Cursor.

## Issues I Ran Into & How I Solved Them

### Issue 1: Git Not Recognized in Cursor Terminal
- After connecting Git via browser to Cursor. I tried to clone the Git repo which I couldn't. I diagnosed the problem and installed the Git SCM app for proper connection via a local folder and used Cursor terminal as a code editor.
- Checked box during Git app installation: *Git from the command line and also from 3rd-party software*.

### Issue 2: Couldn't Clone the Repository
Problem - I was unsure how to link the GitHub repository to the local cursor folder.
Solution 
- I watched the YouTube tutorial for fast and reliable setup.
- Copied the HTTPS URL from the GitHub repo.
- Ran <Git Clone (repo URL)>

### Issue 3: GitHub Login / Push Authentication Error
Problem: When pushing to GitHub, I got an error about user.name and user.email not being configured.
Solution: Ran the global user command with my username and email:
-  <git config --global user.name "User Name">
- <git config --global user.email "user_github_email@gmail.com">
- Then re-attempted repo commit and push via cursor pannel. Logged in to Github through authentication window.

### Issue 4: Commit Message Editor Error
Problem: When trying to commit, Cursor opened a COMMIT_EDITMSG file instead of just committing. It was unclear what to do.
Solution: Watched a YouTube tutorial to commit and push Git repo.
- Typed the commit message on line 1 of the file <add readme file>.
- Saved with <ctrl+ S>.
- And commit and push repo several times to check proper function and sync.
