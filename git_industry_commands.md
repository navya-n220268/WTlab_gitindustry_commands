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


### git commit

**Syntax:**  
git commit

**Purpose:**  
Records changes from the staging area into the repository.

**Example:**  
git commit

**Screenshot Proof:**  

![git commit output](git_commit.png)

---

### git commit -m

**Syntax:**  
git commit -m "commit message"

**Purpose:**  
Commits changes with a descriptive message.

**Example:**  
git commit -m "Added new feature"

**Screenshot Proof:**  

![git commit message output](git_commit_m.png)

---

### git commit --amend

**Syntax:**  
git commit --amend

**Purpose:**  
Modifies the most recent commit (message or content).

**Example:**  
git commit --amend

**Screenshot Proof:**  

![git commit amend output](git_commit_amend.png)

---

### git commit --no-edit

**Syntax:**  
git commit --amend --no-edit

**Purpose:**  
Amends the last commit without changing its commit message.

**Example:**  
git commit --amend --no-edit

**Screenshot Proof:**  

![git commit no edit output](git_commit_amend_noedit.png)

### git branch

**Syntax:**  
git branch

**Purpose:**  
Lists all local branches in the repository.

**Example:**  
git branch

**Screenshot Proof:**  

![git branch output](git_branch.png)

---

### git branch -a

**Syntax:**  
git branch -a

**Purpose:**  
Lists all local and remote branches.

**Example:**  
git branch -a

**Screenshot Proof:**  

![git branch all output](git_branch_a.png)

---

### git branch -d

**Syntax:**  
git branch -d <branch_name>

**Purpose:**  
Deletes a branch safely (only if merged).

**Example:**  
git branch -d feature

**Screenshot Proof:**  

![git branch delete output](git_branch_d.png)

---

### git branch -D

**Syntax:**  
git branch -D <branch_name>

**Purpose:**  
Force deletes a branch even if not merged.

**Example:**  
git branch -D feature

**Screenshot Proof:**  

![git branch force delete output](git_branch_Delete.png)

---

### git checkout

**Syntax:**  
git checkout <branch_name>

**Purpose:**  
Switches to an existing branch.

**Example:**  
git checkout main

**Screenshot Proof:**  

![git checkout output](git_checkout.png)

---

### git checkout -b

**Syntax:**  
git checkout -b <branch_name>

**Purpose:**  
Creates a new branch and switches to it.

**Example:**  
git checkout -b feature

**Screenshot Proof:**  

![git checkout b output](git_checkout_b.png)

---

### git switch

**Syntax:**  
git switch <branch_name>

**Purpose:**  
Switches between branches (modern alternative to checkout).

**Example:**  
git switch main

**Screenshot Proof:**  

![git switch output](git_switch.png)

---

### git switch -c

**Syntax:**  
git switch -c <branch_name>

**Purpose:**  
Creates and switches to a new branch.

**Example:**  
git switch -c new-branch

**Screenshot Proof:**  

![git switch create output](git_switch_c.png)


### git merge

**Syntax:**  
git merge <branch_name>

**Purpose:**  
Merges the specified branch into the current branch.

**Example:**  
git merge feature

**Screenshot Proof:**  

![git merge output](git_merge.png)

---

### git merge --no-ff

**Syntax:**  
git merge --no-ff <branch_name>

**Purpose:**  
Merges a branch while creating a merge commit, even if fast-forward is possible.

**Example:**  
git merge --no-ff feature

**Screenshot Proof:**  

![git merge no ff output](git_merge_no_ff.png)


### git remote

**Syntax:**  
git remote

**Purpose:**  
Displays the list of remote repositories.

**Example:**  
git remote

**Screenshot Proof:**  

![git remote output](git_remote.png)

---

### git remote -v

**Syntax:**  
git remote -v

**Purpose:**  
Shows remote repositories with their URLs.

**Example:**  
git remote -v

**Screenshot Proof:**  

![git remote v output](git_remote_v.png)

---

### git remote add

**Syntax:**  
git remote add <name> <repository_url>

**Purpose:**  
Adds a new remote repository.

**Example:**  
git remote add origin https://github.com/user/repo.git

**Screenshot Proof:**  

![git remote add output](git_remote_add.png)

---

### git remote remove

**Syntax:**  
git remote remove <name>

**Purpose:**  
Removes a remote repository.

**Example:**  
git remote remove origin

**Screenshot Proof:**  

![git remote remove output](git_remote_remove.png)

---

### git fetch

**Syntax:**  
git fetch

**Purpose:**  
Fetches updates from remote without merging.

**Example:**  
git fetch

**Screenshot Proof:**  

![git fetch output](git_fetch.png)

---

### git fetch --all

**Syntax:**  
git fetch --all

**Purpose:**  
Fetches updates from all remotes.

**Example:**  
git fetch --all

**Screenshot Proof:**  

![git fetch all output](git_fetch_all.png)

---

### git pull

**Syntax:**  
git pull

**Purpose:**  
Fetches and merges changes from remote.

**Example:**  
git pull

**Screenshot Proof:**  

![git pull output](git_pull.png)

---

### git pull --rebase

**Syntax:**  
git pull --rebase

**Purpose:**  
Fetches and rebases instead of merging.

**Example:**  
git pull --rebase

**Screenshot Proof:**  

![git pull rebase output](git_pull_rebase.png)

---

### git push

**Syntax:**  
git push

**Purpose:**  
Pushes local commits to remote repository.

**Example:**  
git push

**Screenshot Proof:**  

![git push output](git_push.png)

---

### git push -u origin branch-name

**Syntax:**  
git push -u origin <branch_name>

**Purpose:**  
Pushes branch and sets upstream tracking.

**Example:**  
git push -u origin main

**Screenshot Proof:**  

![git push upstream output](git_push_u.png)

---

### git push --force

**Syntax:**  
git push --force

**Purpose:**  
Force pushes changes (overwrites remote history).

**Example:**  
git push --force

**Screenshot Proof:**  

![git push force output](git_push_force.png)