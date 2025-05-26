<a name="readme-top"></a>

# Github
Learn all about github


<div align="center">
<!-- Title: -->
<h1><a href="https://github.com/skthati/skthati.git">All About Github</a> - Github </h1>
</div>

<!-- Table of contents -->
<hr>
<hr>
<ol>
    <li><a href="#basics">Basics</a> </li>
</ol>
<hr>
<hr>


<!-- Basics -->
## Basics <a name="basics"></a>

A video from microsoft about github
https://www.youtube.com/watch?v=9uGS1ak_FGg&ab_channel=MicrosoftDeveloper


Everyday Git commands
https://git-scm.com/docs/everyday


Conventional Commits. Guideline for commit rules
https://www.conventionalcommits.org/en/v1.0.0/


First Contributions
https://github.com/firstcontributions/first-contributions

Markdown language
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

https://github.com/skills/communicate-using-markdown

https://github.com/actions/starter-workflows



   ```
   - ls --> is to show all folders
   - VCS --> Tracks changes to your code or collection of lines

   ```




<p align="right">(<a href="#readme-top">back to top</a>)</p>
<hr>


# 🧾 Git Cheat Sheet (One-Page)

## 🔧 Setup
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

---

## 📁 Start a Repo
```bash
git init                          # Initialize new repo
git clone <repo-url>             # Clone remote repo
```

---

## 🌿 Branching
```bash
git branch                       # List branches
git branch <name>                # Create new branch
git checkout <name>              # Switch to branch
git checkout -b <name>           # Create and switch to new branch
git switch -c <name>             # Modern way to create & switch
git branch -m <new-name>         # Rename current branch
git branch -M <new-name>         # Force rename branch
```

---

## ✍️ Making Changes
```bash
git status                       # See current changes
git add .                        # Stage all changes
git add <file>                   # Stage specific file
git commit -m "Message"          # Commit staged changes
git diff                         # Show unstaged changes
git diff --staged                # Show staged changes
```

---

## 🔄 Syncing with Remote
```bash
git remote -v                    # View remotes
git push -u origin <branch>      # Push new branch and track it
git push                         # Push to tracked branch
git pull                         # Pull & merge latest changes
git pull --rebase                # Pull with rebase (linear history)
git fetch                        # Download remote changes (no merge)
```

---

## 🗑️ Undoing Changes
```bash
git restore <file>               # Discard unstaged changes (Git 2.23+)
git checkout -- <file>           # Discard unstaged changes (older)
git reset HEAD <file>            # Unstage a staged file
git reset --soft HEAD~1          # Undo last commit (keep changes)
git reset --hard HEAD~1          # Undo last commit (discard changes)
```

---

## 🧼 Clean Up
```bash
git stash                        # Save uncommitted changes
git stash pop                    # Reapply last stashed changes
git branch -d <name>             # Delete local branch (merged)
git branch -D <name>             # Force delete local branch
git push origin --delete <name>  # Delete remote branch
```

---

## 🔍 Logs & History
```bash
git log                          # View commit history
git log --oneline                # Condensed history
git blame <file>                 # See who changed what
```

---

## 💡 Tips
- Use **descriptive branch names** like `feature/login-form` or `bugfix/payment-issue`
- Always `git pull` before starting work
- Commit often with clear messages


<p align="right">(<a href="#readme-top">back to top</a>)</p>
<hr>

## Simple Git steps


    ✅  Fork the repository
        > git fork "url-to-repo"
    ✅  Create a branch or modify branch name
        > git switch -c "new-branch-name"
    ✅  Make changes to your code.
    ✅  stage your changes
        > git add .
        or
        > git add path/to/file
    ✅  Commit your changes
        > git commit -m "Update readme.md" 
    ✅  Push new branch to remote
        > git push -u origin new-branch-name
    ✅  Create a Pull Request (PR)
        > Go to github repo, click 'compare & pull request', describe changes
        and submit PR for review
    ✅  PR merge




<!-- Dotted Line -->
## Git Terminology <a name="dotted-line"></a>



- ### Working Tree

   ```
   Directory and files where you are currently working on.
   ```

- ### Repository (repo)
   ```
   Directory located on top level of working tree where Git keeps all the history.

   - Generally stored as project.git

   ```


- ### Object
   ```
   - blob --> ordinary file
   - tree --> represents directory
   - commit --> specific version of working tree
   - tag --> name of that commit
   ```

- ### Commit
   ```
   - Once commit is made, Changes are visible to others to see
   
   - A file as several states in git.
        - Untracked --> git doesn't know about this file. (first time file created)
        - Tracked --> Actively monitored
            - Unmodified
            - Modified
            - Staged
            - Commited
   ```

- ### Branch
   ```
   - Branches are best way to experiment with your code before merging to main branch
   - Collection of linked commits. 
   - Main --> Main is when a repository is initialized.
   - HEAD --> Current branch is called as head.
   
   - git checkout -b "new-branch-name"
   ```

- ### Pull requests

    Signalling your code is ready to be merged with main branch.


- ### Github Flow

    Github flow cycle.

      ✅  Create feature branch from main branch
      ✅  Write your code in child branch
      ✅  Commit your code.
      ✅  Create a pull request (PR)
      ✅  Let PR be reviewed and approved.
      ✅  Merge into main branch.
      ✅  You can delete the child branch (So that no one will use that branch)
    

    ![alt text](2-branching.png)

- ### Github Issues
    GitHub Issues are used to track ideas, feedback, tasks, or bugs for work on GitHub

- ### Discussions
    Not related to code and meant to have open conversations in public

- ### Github Code Scanning
      GitHub code scanning to identify, resolve, and prevent insecure coding patterns.

- ### CodeQL
      CodeQL is a static analysis testing tool that helps you identify security weaknesses such as SQL injection, cross-site scripting, and code injection issues

- ### Github Actions
      Github Actions is the automation and CI/CD platform that allows you to automate your build, test, and deployment pipeline. You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.

    https://docs.github.com/en/actions/about-github-actions/understanding-github-actions

- ### Github Copilot
      Github Copilot helps you write code faster with less work.

- Remote
   ```
   another repo created remotely when a repo is created.
   - origin --> name created for remote repo
   ```

- Commands, Sub commands, options
   ```
   - Commands --> git
   - Sub-commands --> push, pull
   - options --> - or --, --hard
   ```


<p align="right">(<a href="#readme-top">back to top</a>)</p>
<hr>


- Git and Github
   ```
   Git is version control system and Github is remote repo.
   - Github has additional functionalities like issues, discussions, actions, labels

   ```
- Git version
   ```git
   git --version
   ```

- git commands
   ```git
   - git config --global user.name "SandeepThati"
   - git config --global user.email "sandeep@thati.org"
   - git config --list //To check changes are made
   - Go to the folder
   - git init // To initialize git folder
   - Or git init --initial-branch=main // new repo with initial branch name = main
   - Or git init -b main
   - echo "# gitlearning" >> README.md // Add readme.md
   - git add . // add git
   - git commit -m "Initial commit"
   - git remote add origin https://github.com/skthati/gitlearning.git // Push an 
   existing repository from command line.
   - git branch -M main //Rename old branch to new branch name.
   - git push -u origin main
   - git status // Shows the status of working branch
   - ls -a // To check if git files exists
   ```

- Create new branch
    ```
    git switch -c new-branch-name

    or 

    git checkout -b new-branch-name
    ```

- Push new branch to remote
    ```
    git push -u origin new-branch-name

    ```
- Git Rules
    ```
    ✅  Create or switch to new branch
    ✅  Make your code changes
    ✅  check the status of changed files
        > git status
    ✅  stage your changes
        > git add .
        or
        > git add path/to/file
    ✅  Commit your changes
        > git commit -m "Update readme.md" 
    ✅  Push new branch to remote
        > git push -u origin new-branch-name
    ✅  Create a Pull Request (PR)
        > Go to github repo, click 'compare & pull request', describe changes
        and submit PR for review
    ✅  PR merge
    
    ```

- Git fetch and git merge
    ```
    ✅  > git fetch
        > git merge
    ✅  above two commands are equal to 
        > git push 
    ```

- git status
   ```git
   - Shows the status of working directory
   ```

- git add
   ```git
   - Staging area where git keeps track of the files which are changed
   ```

- git commit
   ```git
   - taking a snapshot of the changes
   ```
- git log
   ```git
   - allows to see commit changes.
   ```

- What is Git repository
   ```
   - Repository contains all project files and version history.
   - Your work, track changes, revision history
   ```

# Git Terminology

### Working Tree
- Directory structure that contains all of the project files.

### Repository
- Top level of working tree

### Clone
- Creating a copy of remote repository

### Fork
- Remote repo which we do not have access.
- Contributing to someone else project. by creating own copy of remote repo

### Commit
- Snapshot of the changes made to files in a repo. Record and save changes

### Staging area
- Immediate area where changes to files are prepared before they are committed. Developers can choose what to commit.

### Branch
- Distinct version of project

#### Head
- working branch is head.

### Merge
- Combining changes of one branch to main branch.

### Blobs
- Individual files

### Tree
- Working tree

### Commit
- Specific version of working tree

### Tag
- Label assigned to individual commit

### Remote
- Reference to Default repo

### Pull
- Action of fetching changes from remote repository to current branch

### Push
- Local commits to remote repository

### Fetch
- Retrieve changes from remote repository. This allows to review before applying the merge

### Pull request
- Request for the changes to be merged to the target branch.

### Remote Repositories
- facilitates interaction among distributed teams

### Collaboration tools
- features like issues, discussions, pull requests, notifications, labels, actions, forks, wikis and projects.

### Branch protection
- enforcing conditions before merging.

# GitHub Flow
- Creating a repository
- Creating a branch
- Making changes to a branch
- Creating a pull request
- Reviewing a pull request
- Addressing review comments
- Merging pull request
- Deleting the branch






- 

# Courses to be Completed

https://learn.microsoft.com/en-us/training/paths/github-actions/


### Devops foundations

https://learn.microsoft.com/en-in/training/paths/devops-foundations-core-principles-practices/




<p align="right">(<a href="#readme-top">back to top</a>)</p>
<hr>







- 👨‍💻 All of my projects are available at [https://github.com/skthati](https://github.com/skthati)

- 📫 How to reach me **sandeep@thati.org**

- 📄 Know about my experiences [https://thati.org/](https://thati.org/)

