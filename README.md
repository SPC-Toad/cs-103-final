# Git and GitHub Guide for Beginners

Welcome to the beginner's guide to using Git and GitHub! This guide will help you understand how to use Git commands to manage your code repositories. We'll focus on the following commands:

- `git clone`
- `git add .`
- `git commit -m "Your message"`
- `git push`
- `git pull`

Let's get started!

---

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Setting Up Git](#setting-up-git)
3. [Cloning a Repository (`git clone`)](#cloning-a-repository-git-clone)
4. [Adding Changes (`git add .`)](#adding-changes-git-add-)
5. [Committing Changes (`git commit -m "message"`)](#committing-changes-git-commit--m-message)
6. [Pushing Changes (`git push`)](#pushing-changes-git-push)
7. [Pulling Updates (`git pull`)](#pulling-updates-git-pull)
8. [Additional Resources](#additional-resources)

---

## Prerequisites

- **Git Installed**: You need to have Git installed on your computer.
  - **Download Git**: [https://git-scm.com/downloads](https://git-scm.com/downloads)
- **GitHub Account**: Sign up for a free account at [https://github.com](https://github.com)

---

## Setting Up Git

Before you start using Git, set your username and email in your terminal or command prompt:

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

---

## Cloning a Repository (`git clone`)

Cloning a repository means copying it from GitHub to your local machine.

1. **Find the Repository URL**:
   - Go to the GitHub repository page you want to clone.
   - Click the green **Code** button.
   - Copy the URL (HTTPS recommended).

2. **Clone the Repository**:
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to place the repository.
   - Run the following command:

     ```bash
     git clone https://github.com/username/repository-name.git
     ```

   - Replace `https://github.com/username/repository-name.git` with the URL you copied.

**Example**:

```bash
git clone https://github.com/octocat/Hello-World.git
```

---

## Adding Changes (`git add .`)

After making changes to your files, you need to stage them before committing.

- **Stage All Changes**:

  ```bash
  git add .
  ```

  - The `.` adds all modified and new files in the current directory and subdirectories.

---

## Committing Changes (`git commit -m "message"`)

Once your changes are staged, you can commit them with a descriptive message.

- **Commit Changes**:

  ```bash
  git commit -m "Describe your changes here"
  ```

**Example**:

```bash
git commit -m "Add new feature to improve user login"
```

---

## Pushing Changes (`git push`)

After committing, push your changes to the remote repository on GitHub.

- **Push Changes**:

  ```bash
  git push
  ```

- **First-Time Push** (if required):

  ```bash
  git push -u origin main
  ```

  - Replace `main` with the name of your branch if it's different.

---

## Pulling Updates (`git pull`)

To update your local repository with changes from the remote repository:

- **Pull Changes**:

  ```bash
  git pull
  ```

This command fetches and merges changes from the remote repository to your local repository.

---

## Additional Resources

- **Git Documentation**: [https://git-scm.com/doc](https://git-scm.com/doc)
- **GitHub Guides**: [https://guides.github.com](https://guides.github.com)
- **Git Cheat Sheet**: [https://education.github.com/git-cheat-sheet-education.pdf](https://education.github.com/git-cheat-sheet-education.pdf)
