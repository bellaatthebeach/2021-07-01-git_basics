# git basics

- `git init`: initialize git repository in current working directory
- `git status`: status
- `git add <file>`: adds <file> to the staging area
- `git commit`: creates a commit, you provide commit message
- `git log`: shows log of commits
	- `git log --oneline`: shows one line version of log with addresses
- `HEAD`: version of file you have on your computer
- `git diff HEAD~<NUM> <FILE>`: compares current file to file<NUM> revisions ago
	- `git diff <HASH> <FILE>`: compares current file (at head) to <HASH> version

# remotes
- `ssh-keygen`: create ssh keys (once)
- `git remote add <URL>`: adds the URL
- `git push origin main`: push to the main branch to the origin remote
	
