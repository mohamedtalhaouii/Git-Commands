### **Git Commands Index**

- **[Installation & GUIs](#installation--guis)**
- **[Setup](#setup)**
- **[Setup & Init](#setup--init)**
- **[Stage & Snapshot](#stage--snapshot)**
- **[Branch & Merge](#branch--merge)**
- **[Inspect & Compare](#inspect--compare)**
- **[Tracking Path Changes](#tracking-path-changes)**
- **[Ignoring Patterns](#ignoring-patterns)**
- **[Share & Update](#share--update)**
- **[Rewrite History](#rewrite-history)**
- **[Temporary Commits](#temporary-commits)**

## **Installation & GUIs**  

| Command/Link | Description |  
|-------------|------------|  
| [GitHub for Windows](https://windows.github.com) | Windows installer for Git with GUI |  
| [GitHub for Mac](https://mac.github.com) | Mac installer for Git with GUI |  
| [Git for All Platforms](http://git-scm.com) | Official Git download for Linux/Solaris |  



## **Setup**  

| Command | Description |  
|---------|------------|  
| `git config --global user.name "[firstname lastname]"` | Set a name for commit attribution |  
| `git config --global user.email "[valid.email]"` | Set an email for commit attribution |  
| `git config --global color.ui auto` | Enable colored command-line output |  



## **Setup & Init**  

| Command | Description |  
|---------|------------|  
| `git init` | Initialize a directory as a Git repository |  
| `git clone [url]` | Clone a repository from a URL |  



## **Stage & Snapshot**  

| Command | Description |  
|---------|------------|  
| `git status` | Show modified files in working directory |  
| `git add [file]` | Stage a file for commit |  
| `git reset [file]` | Unstage a file (keeps changes) |  
| `git diff` | Show unstaged changes |  
| `git diff --staged` | Show staged changes |  
| `git commit -m "[descriptive message]"` | Commit staged changes |  



## **Branch & Merge**  

| Command | Description |  
|---------|------------|  
| `git branch` | List branches (* marks current branch) |  
| `git branch [branch-name]` | Create a new branch |  
| `git checkout` | Switch to another branch |  
| `git merge [branch]` | Merge a branch into the current one |  
| `git log` | Show commit history |  



## **Inspect & Compare**  

| Command | Description |  
|---------|------------|  
| `git log branchB...branchA` | Show commits in branchA not in branchB |  
| `git log --follow [file]` | Show file history, including renames |  
| `git diff branchB...branchA` | Show changes in branchA not in branchB |  
| `git show [SHA]` | Show object details in readable format |  



## **Tracking Path Changes**  

| Command | Description |  
|---------|------------|  
| `git rm [file]` | Delete file and stage removal |  
| `git mv [existing-path] [new-path]` | Rename/move file and stage change |  
| `git log --stat -M` | Show commit logs with moved paths |  



## **Ignoring Patterns**  

| Pattern/Command | Description |  
|----------------|------------|  
| `logs/` `*.notes` `pattern*/` | Example `.gitignore` entries |  
| `git config --global core.excludesfile [file]` | Set a global ignore file |  



## **Share & Update**  

| Command | Description |  
|---------|------------|  
| `git remote add [alias] [url]` | Add a remote repository alias |  
| `git fetch [alias]` | Fetch all branches from remote |  
| `git merge [alias]/[branch]` | Merge a remote branch |  
| `git push [alias] [branch]` | Push local commits to remote |  
| `git pull` | Fetch and merge from remote |  



## **Rewrite History**  

| Command | Description |  
|---------|------------|  
| `git rebase [branch]` | Reapply current branch commits onto another |  
| `git reset --hard [commit]` | Reset to a commit (clears changes) |  



## **Temporary Commits**  

| Command | Description |  
|---------|------------|  
| `git stash` | Temporarily save modified files |  
| `git stash list` | List stashed changes |  
| `git stash pop` | Restore top stashed changes |  
| `git stash drop` | Discard top stashed changes |  

---

<h3 align="center"> 🧑🏻‍💻 | Made By : <a href="https://github.com/mohamedtalhaouii" target="_blank">Mohamed Talhaoui</a></h3>

