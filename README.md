# Git Courses


# Git Courses

This repository contains the courses I've completed for learning Git. Below are the links and details for each course.

## Courses

### 1. Neom Course - [Git Course Neom](https://www.youtube.com/watch?v=TEx_mRpIDkA&t=145s)
   - This course covers the fundamental concepts of Git. It teaches how to create repositories, work with branches, make commits and pushes, and manage folder changes in Git.

### 2. Jadi Course - [Git Course Jadi](https://www.youtube.com/watch?v=utuny8WH-3U&list=PLwSYhER2SPaOQ5MMh29DqpYbpExXthlqW)
   - This comprehensive course provides a complete guide to working with Git. It explains the usage of various Git commands such as `git status`, `git log`, and `git merge` in detail.

## GitHub Basics

Here are some basic Git commands and steps you'll need when working with GitHub:

### 1. **Clone a GitHub repository:**
   To copy a repository from GitHub to your local machine:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

### 2. **Check repository status:**
   To see the current status of your working directory (e.g., modified files):
   ```bash
   git status
   ```

### 3. **Add files to staging:**
   To add files that you want to commit:
   ```bash
   git add filename
   ```
   To add all modified files:
   ```bash
   git add .
   ```

### 4. **Commit changes:**
   To commit the added files with a descriptive message:
   ```bash
   git commit -m "Your commit message"
   ```

### 5. **Push changes to GitHub:**
   To push your local commits to the remote GitHub repository:
   ```bash
   git push origin main
   ```
   (Replace `main` with the name of your branch if it's different.)

### 6. **Pull changes from GitHub:**
   To fetch and merge changes from the GitHub repository into your local branch:
   ```bash
   git pull origin main
   ```

### 7. **Create a new branch:**
   To create a new branch and switch to it:
   ```bash
   git checkout -b new-branch-name
   ```

### 8. **Switch branches:**
   To switch between different branches:
   ```bash
   git checkout branch-name
   ```

### 9. **Merge branches:**
   To merge one branch into another (for example, merging a feature branch into `main`):
   ```bash
   git checkout main
   git merge feature-branch
   ```

### 10. **View commit history:**
   To view the commit history of the repository:
   ```bash
   git log
   ```

## How to Use

You can use this repository as a reference for the courses. Files related to each course are available in their respective folders.

## Contributing

If you have any useful resources or content you'd like to add to this repository, feel free to submit a pull request.
