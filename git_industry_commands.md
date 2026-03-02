# Industry-Level Git & GitHub Commands Practice

---

## 1. Git Configuration Commands

### 1.1 git config --global user.name

**Syntax:**
git config --global user.name "Your Name"

**Purpose:**
Sets the global username used for all Git commits on this system.

**Example:**
git config --global user.name "Mehanaz Shaik"

**Screenshot Proof:**
(Add screenshot here after executing command)

---

### 1.2 git config --global user.email

**Syntax:**
git config --global user.email "your@email.com"

**Purpose:**
Sets the global email used for all Git commits.

**Example:**
git config --global user.email "mehanaz@gmail.com"

**Screenshot Proof:**
(Add screenshot here)

---

### 1.3 git config --list

**Syntax:**
git config --list

**Purpose:**
Displays all configured Git settings.

**Example:**
git config --list

**Screenshot Proof:**
(Add screenshot here)

---

## 2. Repository Setup Commands

### 2.1 git init

**Syntax:**
git init

**Purpose:**
Initializes a new Git repository in the current directory.

**Example:**
git init

**Screenshot Proof:**
(Add screenshot after running command in a new folder)

---

### 2.2 git clone

**Syntax:**
git clone <repository-url>

**Purpose:**
Creates a copy of an existing remote repository to your local system.

**Example:**
git clone https://github.com/username/repository.git

**Screenshot Proof:**
(Add screenshot here)

---

### 2.3 git clone --branch

**Syntax:**
git clone --branch <branch-name> <repository-url>

**Purpose:**
Clones a specific branch from a repository.

**Example:**
git clone --branch master https://github.com/username/repository.git

**Screenshot Proof:**
(Add screenshot here)

---

### 2.4 git clone --depth

**Syntax:**
git clone --depth 1 <repository-url>

**Purpose:**
Clones repository with limited commit history (shallow clone).

**Example:**
git clone --depth 1 https://github.com/username/repository.git

**Screenshot Proof:**
(Add screenshot here)

---

## 3. Repository Status & Inspection Commands

### 3.1 git status

**Syntax:**
git status

**Purpose:**
Displays the current state of the working directory and staging area.

**Example:**
git status

**Screenshot Proof:**
(Add screenshot here)

---

### 3.2 git log

**Syntax:**
git log

**Purpose:**
Shows detailed commit history.

**Example:**
git log

**Screenshot Proof:**
(Add screenshot here)

---

### 3.3 git log --oneline

**Syntax:**
git log --oneline

**Purpose:**
Displays commit history in compact one-line format.

**Example:**
git log --oneline

**Screenshot Proof:**
(Add screenshot here)

---

### 3.4 git log --graph

**Syntax:**
git log --graph --oneline --all

**Purpose:**
Displays commit history in graphical tree format.

**Example:**
git log --graph --oneline --all

**Screenshot Proof:**
(Add screenshot here)

---

### 3.5 git show

**Syntax:**
git show <commit-id>

**Purpose:**
Shows detailed information about a specific commit.

**Example:**
git show abc123

**Screenshot Proof:**
(Add screenshot here)

---

### 3.6 git diff

**Syntax:**
git diff

**Purpose:**
Shows differences between working directory and staging area.

**Example:**
git diff

**Screenshot Proof:**
(Add screenshot here)

---

### 3.7 git diff --staged

**Syntax:**
git diff --staged

**Purpose:**
Shows differences between staging area and last commit.

**Example:**
git diff --staged

**Screenshot Proof:**
(Add screenshot here)

---

### 3.8 git blame

**Syntax:**
git blame <file-name>

**Purpose:**
Shows who modified each line of a file.

**Example:**
git blame git_industry_commands.md

**Screenshot Proof:**
(Add screenshot here)

---

### 3.9 git reflog

**Syntax:**
git reflog

**Purpose:**
Shows history of all branch movements and HEAD changes.

**Example:**
git reflog

**Screenshot Proof:**
(Add screenshot here)

---

### 3.10 git shortlog

**Syntax:**
git shortlog

**Purpose:**
Summarizes commit history by author.

**Example:**
git shortlog

**Screenshot Proof:**
(Add screenshot here)

---

Testing file tracking section