# Growth-Marketing-Project - Portfolio Setup

---

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

---

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

---

## Research Project: LinkedIn Organic Content Strategy for B2B SaaS

### Why I Chose This Topic
LinkedIn organic content is one of the highest-ROI growth channels for B2B SaaS companies today. Companies like to spend less on organic and it also help build long-term brand authority, generates inbound leads, and compounds over time.

I chose this topic to study what separates practitioners who generate real revenue from LinkedIn versus those who simply collect likes and impressions.

### Selection Criteria
Three strict criteria applied to every expert:
- Actively posting on LinkedIn as a primary channel.
- Specific, documented business outcomes from LinkedIn organic.
- Focused on B2B SaaS, not general creators or solopreneurs.

## What This Repository Contains

- Expert source list
- LinkedIn post examples
- YouTube transcripts
- Podcast notes
- Research notes and content pattern analysis

### Repository Structure

- `LinkedIn organic content strategy for B2B SaaS/Research/Source.md`
- `Research/LinkedIn-posts/`
- `Research/YouTube-Transcripts/`
- `Research/Others/`

### The 10 Experts Selected

| # | Expert | Role | Why Selected |
|---|---|---|---|
| 1 | Adam Robinson | Founder, Retention.com + RB2B | $1M ARR in 16 weeks via LinkedIn founder content |
| 2 | Devin Reed | Founder, The Reeder | Built 95-5 Content System at Gong during $20M→$200M ARR growth |
| 3 | Peep Laja | CEO, Wynter | 80% of Wynter demo requests come directly from LinkedIn |
| 4 | Brendan Hufford | Founder, Growth Sprints | B2B SaaS content specialist with documented pipeline outcomes |
| 5 | Diandra Escobar | CEO, Distinctiva | Built Distinctiva past $1M revenue through founder-led LinkedIn content |
| 6 | Anthony Pierri | Co-founder, Fletch PMM | Helped 500+ B2B SaaS companies clarify positioning for LinkedIn content |
| 7 | Gal Aga | CEO, Aligned | 65% of Aligned's leads come directly from LinkedIn organic |
| 8 | Dave Gerhardt | Founder, Exit Five | Built 40,000+ member B2B marketing community through LinkedIn content |
| 9 | Amanda Natividad | Chief Evangelist, SparkToro | Pioneered Zero Click Marketing — the dominant B2B LinkedIn strategy |
| 10 | Chris Walker | CEO, Refine Labs | Grew Refine Labs to serve 300+ B2B SaaS companies via LinkedIn demand creation |

## Research Workflow

1. Collect expert sources
2. Save LinkedIn post links/content
3. Fetch YouTube transcripts where available
4. Add podcast/source notes where no transcript exists
5. Analyze patterns across experts

## Tools Used for Collection

- Cursor
- GitHub
- Git
- Supadata API (to fetch YouTube Transcipts through urls)
- Manual LinkedIn post collection and annotation
- Profile and content analysis across LinkedIn, YouTube, and newsletters