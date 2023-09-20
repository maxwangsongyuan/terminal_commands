# terminal_commands

---

### **File and Directory Management**

---

**Directory Operations:**

- **Create a New Directory:** 
  ```bash
  mkdir <dirname>
  ```

- **Create Nested Directories:** 
  ```bash
  mkdir -p dir1/dir2/dir3
  ```

- **Change Directory:** 
  ```bash
  cd <dirname>
  ```

- **Move Up One Directory:** 
  ```bash
  cd ..
  ```

- **Go to Home Directory:** 
  ```bash
  cd
  ```

- **Print Current Directory:** 
  ```bash
  pwd
  ```

- **Remove Directory and Contents:** 
  ```bash
  rm -r <dirname>
  ```

- **Forcefully Remove Directory:** 
  ```bash
  rm -rf <dirname>
  ```

---

**File Operations:**

- **Create/Update File:** 
  ```bash
  touch <filename>
  ```

- **Remove File:** 
  ```bash
  rm <filename>
  ```

- **Forcefully Remove File:** 
  ```bash
  rm -f <filename>
  ```

- **Display Text:** 
  ```bash
  echo "<text>"
  ```

- **Append Text to File:** 
  ```bash
  echo "<text>" >> <filename>
  ```

- **Open in Vim:** 
  ```bash
  vim <filename>
  ```

---

### **Git Workflow**

---

**Initialization & Cloning:**

- **Initialize Git Repository:** 
  ```bash
  git init
  ```

- **Clone a Repository:** 
  ```bash
  git clone https://...
  ```

---

**Inspecting & Comparing:**

- **Display Workspace State:** 
  ```bash
  git status
  ```

- **Show Commit Logs:** 
  ```bash
  git log
  ```

- **Graphical Display of Commits:** 
  ```bash
  git log --graph --pretty --oneline --all
  ```

- **Commit Logs with Differences:** 
  ```bash
  git log -p
  ```

---

**Branching & Navigation:**

- **View All Branches:** 
  ```bash
  git branch -vv
  ```

- **Switch to a Branch:** 
  ```bash
  git checkout <branch_name>
  ```

- **Create and Switch to New Branch:** 
  ```bash
  git checkout -b <branch_name>
  ```

---

**Staging & Committing:**

- **Choose Patches to Stage:** 
  ```bash
  git add -p
  ```

- **Commit with a Message:** 
  ```bash
  git commit -m "message"
  ```

- **Modify Latest Commit:** 
  ```bash
  git commit --amend
  ```

---

**Rebasing & Merging:**

- **Interactively Rebase Last N Commits:** 
  ```bash
  git rebase -i HEAD~N
  ```

- **Pull and Rebase:** 
  ```bash
  git pull —rebase
  ```

---

**Push & Pull:**

- **Fetch and Merge Changes:** 
  ```bash
  git pull
  ```

- **Push Changes:** 
  ```bash
  git push
  ```

---

**Resetting & Restoring:**

- **Reset to a Commit:** 
  ```bash
  git reset --soft/hard <commit>
  ```

- **Unstage or Overwrite File Changes:** 
  ```bash
  git restore <filename>
  ```

- **Show or Remove Untracked Files:** 
  ```bash
  git clean -d -n/f
  ```

---

### **File and Directory Transfer**

---

**Secure Copy Operations:**

- **Securely Copy a File:** 
  ```bash
  scp <source> <destination>
  ```

- **Securely Copy a Directory:** 
  ```bash
  scp -r cloudpath localpath
  ```

---


