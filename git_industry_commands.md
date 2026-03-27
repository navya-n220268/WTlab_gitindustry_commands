# Git Industry Level Commands Documentation

## 1. Git Configuration Commands

### git config --global user.name

**Syntax:**
git config --global user.name "Your Name"

**Purpose:**
Sets the global username that will appear in your Git commits.

**Example:**
git config --global user.name "Navya-220268"

**Output Screenshot:**
![git init screenshot](user_config.png)


### git config --global user.email

**Syntax:**
git config --global user.email

**Purpose:**
Sets the global email address that will appear in your Git commits.

**Example:**
git config --global user.email "n220268@rguktn.ac.in"

**Output Screenshot:**
![git init screenshot](mail_config.png)


### git config --list

**Purpose:**
Displays all the Git configuration settings currently applied.

**Output Screenshot:**
![git init screenshot](list.png)


## Repository set up commands

### git init

**Purpose:**
Creates a new Git repository in the current folder.

**Output Screenshot:**
![git init screenshot](gitinit.png)


### git clone

**Syntax:**
git clone "repo-link"

**Purpose:**
Copies an existing remote repository to your local system.

**Example:**
git clone https://github.com/navya-n220268/WTlab_gitindustry_commands.git

**Output Screenshot:**
![git init screenshot](clone.png)


### git clone --branch

**Syntax:**  
git clone --branch <branch_name> <repository_url>

**Purpose:**  
Clones a specific branch from a repository instead of the default branch.

**Example:**  
git clone --branch main https://github.com/navya-n220268/WTlab_gitindustry_commands.git

**Screenshot Proof:**  

![git clone branch output](clone_branch.png)

---

### git clone --depth

**Syntax:**  
git clone --depth <number> <repository_url>

**Purpose:**  
Creates a shallow clone with limited commit history to reduce download size.

**Example:**  
git clone --depth 1 https://github.com/navya-n220268/WTlab_gitindustry_commands.git

**Screenshot Proof:**  

![git clone depth output](clone_depth.png)

---

### git status

**Syntax:**  
git status

**Purpose:**  
Displays the current state of the working directory and staging area.
https
**Example:**  
git status

**Screenshot Proof:**  

![git status output](git_status.png)

---

### git log

**Syntax:**  
git log

**Purpose:**  
Shows detailed commit history of the repository.

**Example:**  
git log

**Screenshot Proof:**  

![git log output](git_log.png)

---

### git log --oneline

**Syntax:**  
git log --oneline

**Purpose:**  
Displays commit history in a compact one-line format.

**Example:**  
git log --oneline

**Screenshot Proof:**  

![git log oneline output](git_log_oneline.png)

---

### git log --graph

**Syntax:**  
git log --graph

**Purpose:**  
Displays commits in a graphical tree structure.

**Example:**  
git log --graph

**Screenshot Proof:**  

![git log graph output](git_log_graph.png)

---

### git show

**Syntax:**  
git show <commit_id>

**Purpose:**  
Shows detailed information about a specific commit.

**Example:**  
git show HEAD

**Screenshot Proof:**  

![git show output](git_show.png)

---

### git diff

**Syntax:**  
git diff

**Purpose:**  
Shows changes between working directory and staging area.

**Example:**  
git diff

**Screenshot Proof:**  

![git diff output](git_diff.png)

---

### git diff --staged

**Syntax:**  
git diff --staged

**Purpose:**  
Shows differences between staged changes and last commit.

**Example:**  
git diff --staged

**Screenshot Proof:**  

![git diff staged output](git_diff_staged.png)

---

### git blame

**Syntax:**  
git blame <file_name>

**Purpose:**  
Displays who last modified each line of a file.

**Example:**  
git blame index.html

**Screenshot Proof:**  

![git blame output](git_blame.png)

---

### git reflog

**Syntax:**  
git reflog

**Purpose:**  
Shows history of all HEAD movements and commits.

**Example:**  
git reflog

**Screenshot Proof:**  

![git reflog output](git_reflog.png)

---

### git shortlog

**Syntax:**  
git shortlog

**Purpose:**  
Summarizes commit history grouped by author.

**Example:**  
git shortlog

**Screenshot Proof:**  

![git shortlog output](git_shortlog.png)

### git add

**Syntax:**  
git add <file_name>

**Purpose:**  
Adds a specific file to the staging area.

**Example:**  
git add git_industry_commands.md

**Screenshot Proof:**  

![git add output](git_add.png)

---

### git add .

**Syntax:**  
git add .

**Purpose:**  
Adds all files in the current directory to the staging area.

**Example:**  
git add .

**Screenshot Proof:**  

![git add dot output](git_add_all.png)

---

### git add -p

**Syntax:**  
git add -p

**Purpose:**  
Allows adding changes interactively in parts (hunks).

**Example:**  
git add -p

**Screenshot Proof:**  

![git add patch output](git_add_p.png)

---

### git restore

**Syntax:**  
git restore <file_name>

**Purpose:**  
Restores a file to its last committed state.

**Example:**  
git restore git_industry_commands.md

**Screenshot Proof:**  

![git restore output](git_restore.png)

---

### git restore --staged

**Syntax:**  
git restore --staged <file_name>

**Purpose:**  
Removes a file from the staging area.

**Example:**  
git restore --staged git_industry_commands.md

**Screenshot Proof:**  

![git restore staged output](git_restore_staged.png)

---

### git rm

**Syntax:**  
git rm <file_name>

**Purpose:**  
Removes a file from the repository and staging area.

**Example:**  
git rm file.txt

**Screenshot Proof:**  

![git rm output](git_rm.png)

---

### git mv

**Syntax:**  
git mv <old_name> <new_name>

**Purpose:**  
Renames or moves a file in the repository.

**Example:**  
git mv old.txt new.txt

**Screenshot Proof:**  

![git mv output](git_mv.png)