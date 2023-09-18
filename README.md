# terminal_commands

---

### **File and Directory Management**

**Directory Operations:**
- `mkdir <dirname>`: Create a new directory.
  - `mkdir -p dir1/dir2/dir3`: Create nested directories.
  
- `cd <dirname>`: Change the current directory.
  - `cd ..`: Move up one directory.
  - `cd`: Go to home directory.
  
- `pwd`: Print the current working directory.
  
- `rm -r <dirname>`: Remove a directory and its contents.
  - `rm -rf <dirname>`: Forcefully remove a directory and its contents.

**File Operations:**
- `touch <filename>`: Create/update a file.
  
- `rm <filename>`: Remove a file.
  - `rm -f <filename>`: Forcefully remove a file.
  
- `echo "<text>"`: Display text.
  - `echo "<text>" >> <filename>`: Append text to a file.
  
- `vim <filename>`: Open a file in Vim.

---

### **Git Workflow**

**Initialization & Cloning:**
- `git init`: Initialize a new Git repository.
- `git clone https://...`: Clone a repository.

**Inspecting & Comparing:**
- `git status`: Display the state of the workspace.
- `git log`: Show commit logs.
  - `git log --graph --pretty --oneline --all`: Graphical display of commits.
  - `git log -p`: Show commit logs with patch differences.

**Branching & Navigation:**
- `git branch -vv`: View all branches.
- `git checkout <branch_name>`: Switch to a branch.
  - `git checkout -b <branch_name>`: Create and switch to a new branch.

**Staging & Committing:**
- `git add -p`: Interactively choose patches to stage.
- `git commit -m "message"`: Commit with a message.
  - `git commit --amend`: Modify the latest commit.

**Rebasing & Merging:**
- `git rebase -i HEAD~N`: Interactively rebase last N commits.
- `git pull —rebase`: Pull changes and rebase.

**Push & Pull:**
- `git pull`: Fetch and merge changes.
- `git push`: Push changes.

**Resetting & Restoring:**
- `git reset --soft/hard <commit>`: Reset to a commit.
- `git restore <filename>`: Unstage or overwrite changes in files.
- `git clean -d -n/f`: Show or remove untracked files and directories.

---

