Day 1:installed Git and vs code 

# Setup Notes (Day 1-2)

## Tools installed
- GitHub account + repo `agentic-ai-journey`
- Git (git-scm.com)
- VS Code (code.visualstudio.com)

## One-time setup
1. Open terminal in VS Code: Terminal > New Terminal
2. Tell Git who I am:
   git config --global user.name "my-github-username"
   git config --global user.email "my-github-email"
3. Download repo to laptop:
   git clone <HTTPS link from the green Code button>
4. Open the folder: File > Open Folder

## Daily routine (push my work)
git add .
git commit -m "day N: what I did"
git push

## Problems I fixed
- Typo `git add.` -> must be `git add .` (space before the dot)
- Push error "Invalid username or token": removed old GitHub entries in
  Windows Credential Manager, then pushed again and signed in via browser.

## Rules I follow
- Never push API keys. Keep them in a .env file and add `.env` to .gitignore.
- Push something small every day.

Push it

git add .
git commit -m "day 2: add setup notes"
git push