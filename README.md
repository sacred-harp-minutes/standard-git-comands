# standard-git-commands
Notes about using git

- Go to repo on GitHub
- Click on Clone/Download
- Copy the address
- in Terminal type 
  - `git clone <clonedaddressfromGitHub>`
  - `cd <clonedaddressfromGitHub>`

- Create branch
  - `git checkout -b <branchName>`

- Make local changes

- Figure out where you stand? 
  - `git status` (where are things)
  - `git log` (what happened)

- Overwrite local
  `git checkout -- <file>`

- Save change to GitHub
  - `git add <file>`
  - `git commit -m 'MESSAGE'`
  - `git push`
  - tells you what command you need to set up branch on GitHub
  - gives you instructions for creating a pull request on GitHub
  - once you've merged the pull request (on GitHub) you can delete branch
  - but you still have the branch locally
  - `git checkout master` (go back to master branch locally)

- Pull changes into local master branch copy
  - `git pull`
