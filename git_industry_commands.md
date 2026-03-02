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