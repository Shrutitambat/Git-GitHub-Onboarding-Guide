### **Introduction**

Welcome to the ChaiCode Cohort development team! This onboarding guide will help you get started with Git and GitHub, essential tools for version control and team collaboration. Git keeps track of code changes, and GitHub enhances teamwork by providing a shared space for managing repositories, reviewing code, and ensuring smooth collaboration.

---

### **Basics of Git and GitHub**

* **What is Git?**  
    Git is a distributed version control system that tracks changes in your codebase, allows collaboration, and helps resolve conflicts effectively.
    
* **What is GitHub?**  
    GitHub is a web-based platform built around Git. It simplifies sharing, reviewing, and managing repositories in a team environment.
    

---

### **Installation and Setup**

#### **Installing Git**

Follow the steps below based on your operating system:

**Windows**

1. Download Git from [git-scm.com](https://git-scm.com).
    
2. Run the installer and follow the setup instructions.
    
3. Verify installation:
    
    ```plaintext
    git --version
    ```
    

**macOS**

1. Install Git using Homebrew:
    
    ```plaintext
    brew install git
    ```
    
2. Verify installation:
    
    ```plaintext
    git --version
    ```
    

**Linux**

1. Install Git using your package manager:
    
    ```plaintext
    sudo apt-get install git    # Ubuntu/Debian
    sudo yum install git        # CentOS/RedHat
    ```
    
2. Verify installation:
    
    ```plaintext
    git --version
    ```
    

#### **Configuring Git**

Set your username and email globally:

```plaintext
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

#### **Creating a GitHub Account**

1. Visit [github.com](https://github.com) and sign up for an account.
    
2. Verify your email address and set up your profile.
    

---

### **Cloning the ChaiCode Repository**

#### **Clone a Repository**

1. Navigate to the GitHub repository URL.
    
2. Copy the HTTPS link and clone it using:
    
    ```plaintext
    git clone https://github.com/ChaiCode/example-repo.git
    ```
    

#### **Navigate to the Cloned Repository**

```plaintext
cd example-repo
```

---

### **Basic Git Commands**

#### **Commonly Used Commands**

* Check the status of your repository:
    
    ```plaintext
    git status
    ```
    
* Stage changes:
    
    ```plaintext
    git add .
    ```
    
* Commit staged changes:
    
    ```plaintext
    git commit -m "Commit message"
    ```
    
* Push changes to the remote repository:
    
    ```plaintext
    git push
    ```
    
* Pull changes from the remote repository:
    
    ```plaintext
    git pull
    ```
    
* View commit history:
    
    ```plaintext
    git log
    ```
    

---

### **Commit Message Rules**

Follow these rules for writing commit messages:

* Use the present tense (e.g., "Add feature").
    
* Start with a capital letter.
    
* Keep it under 50 characters.
    
* Use prefixes for categorization:
    
    * `feat:` for new features
        
    * `fix:` for bug fixes
        
    * `docs:` for documentation updates
        

Example:

```plaintext
feat: Add tea selection feature  
fix: Resolve login issue for tea enthusiasts  
docs: Update README with chai varieties  
```

---

### **Branching Workflow**

#### **Branching Strategy**

* **main**: The stable branch with production-ready code.
    
* **development**: The integration branch for new features.
    
* **feature/**: Individual branches for specific features or fixes.
    

#### **Creating and Switching Branches**

```plaintext
git branch feature/tea-menu  
git checkout feature/tea-menu  
```

#### **Merging and Resolving Conflicts**

1. Merge feature branch into development:
    
    ```plaintext
    git checkout development  
    git merge feature/tea-menu  
    ```
    
2. Resolve conflicts in your text editor if any arise.
    

---

### **Pull Requests (PR)**

#### **Creating a Pull Request**

1. Push your branch to GitHub.
    
2. Navigate to your repository and click "New Pull Request."
    
3. Fill in the PR description, link it to an issue if applicable, and assign reviewers.
    

---

### **Best Practices**

* Commit frequently to save progress and document changes.
    
* Pull changes regularly to stay updated and avoid conflicts.
    
* Review and test your code before pushing.
