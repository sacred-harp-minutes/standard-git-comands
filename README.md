# standard-git-commands
Notes about using git

1. Clone repo
  - Go to repo on GitHub
  - Click on Clone/Download
  - Copy the address
  - in Terminal type 
    - `git clone <clonedaddressfromGitHub>`
    - `cd <clonedaddressfromGitHub>`

2. Create branch
  - `git checkout -b <branchName>`

3. Make local changes

4. Figure out where you stand? 
  - `git status` (where are things)
  - `git log` (what happened)

5. Overwrite local
  `git checkout -- <file>`

6. Save change to GitHub
  - `git add <file>` (`git add .` adds all files and folders in the current directory)
  - `git commit -m 'MESSAGE'`
  - `git push`
    - tells you what command you need to set up branch on GitHub
    - gives you instructions for creating a pull request on GitHub
    - once you've merged the pull request (on GitHub) you can delete branch
    - but you still have the branch locally
  - `git checkout master` (go back to master branch locally)

7. Pull changes into local master branch copy
  - `git pull`
