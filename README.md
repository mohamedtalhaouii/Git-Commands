### **1. Basic Setup & Config**
```bash
# Set your Git username & email
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

# View Git configuration
git config --list

# Check Git version
git --version
```

---

### **2. Starting a Repository**
```bash
# Initialize a new Git repo
git init

# Clone a remote repository
git clone <repo-url>
```

---

### **3. Making Changes**
```bash
# Check status of changes
git status

# Stage a file or all changes
git add <file>
git add .

# Commit changes
git commit -m "Commit message"

# Stage and commit modified/deleted files (skip untracked)
git commit -am "Commit message"

# Discard unstaged changes
git restore <file>

# Unstage a file (keep changes)
git restore --staged <file>
```

---

### **4. Branching & Merging**
```bash
# List branches
git branch

# Create a new branch
git branch <branch-name>

# Switch to a branch
git checkout <branch-name>

# Create and switch to a new branch
git checkout -b <branch-name>

# Merge a branch into current branch
git merge <branch-name>

# Delete a branch (safe)
git branch -d <branch-name>

# Force-delete a branch
git branch -D <branch-name>
```

---

### **5. Remote Repositories**
```bash
# List remotes
git remote -v

# Add a remote repository
git remote add origin <repo-url>

# Push to remote (first time)
git push -u origin <branch>

# Push changes
git push

# Pull changes
git pull

# Fetch changes without merging
git fetch
```

---

### **6. Undoing Changes**
```bash
# Soft reset (keep changes staged)
git reset --soft <commit>

# Mixed reset (keep changes unstaged)
git reset --mixed <commit>

# Hard reset (DANGER: discard everything)
git reset --hard <commit>

# Revert a commit (safe undo)
git revert <commit>

# Amend the last commit
git commit --amend
```

---

### **7. Viewing History & Diffs**
```bash
# View commit history
git log

# Compact history
git log --oneline

# History with graph
git log --graph

# Show unstaged changes
git diff

# Show staged changes
git diff --staged

# Show changes in a commit
git show <commit>
```

---

### **8. Stashing (Temporary Changes)**
```bash
# Stash changes
git stash

# List stashes
git stash list

# Apply and remove latest stash
git stash pop

# Apply stash (keep it)
git stash apply

# Delete a stash
git stash drop
```

---

### **9. Tags (Versioning)**
```bash
# List tags
git tag

# Create an annotated tag
git tag -a v1.0 -m "Version 1.0"

# Push tags to remote
git push --tags
```

---

### **10. Advanced Commands**
```bash
# Apply a specific commit to current branch
git cherry-pick <commit>

# View reference log (recover lost commits)
git reflog

# Delete untracked files/folders (DANGER)
git clean -fd

# Find bug-introducing commit
git bisect start
git bisect bad
git bisect good <commit>
```

---

### **Cheat Sheet**
```bash
# Daily Workflow:
git add . && git commit -m "message" && git push

# Undo last commit (keep changes):
git reset --soft HEAD~1

# Sync fork with upstream:
git fetch upstream && git merge upstream/main
```
