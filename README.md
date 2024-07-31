# PLPBasicGitAssignment

This repository contains the steps and commands for setting up a basic Git repository, making changes, and pushing those changes to GitHub.

## Task 1: Repository Setup

**1. Create a GitHub Repository:**
   - Log in to [GitHub](https://github.com).
   - Create a new repository named `PLPBasicGitAssignment`.
   - Initialize the repository with a README file.

## Task 2: Local Setup

**2. Local Folder Setup:**
   - Create a new folder on your local machine named `PLPBasicGitAssignment`.
   - Open a terminal or command prompt and navigate to this folder:
     ```bash
     mkdir PLPBasicGitAssignment
     cd PLPBasicGitAssignment
     ```

**3. Git Initialization:**
   - Initialize a new Git repository in this folder:
     ```bash
     git init
     ```

**4. Connect to GitHub:**
   - Add the remote repository URL to your local repository:
     ```bash
     git remote add origin https://github.com/yourusername/PLPBasicGitAssignment.git
     ```

## Task 3: Making Changes

**5. Create a File:**
   - Create a new file named `hello.txt` and add a simple message:
     ```bash
     echo "Hello, Git!" > hello.txt
     ```

**6. Commit the Changes:**
   - Stage the new file for commit:
     ```bash
     git add hello.txt
     ```
   - Commit the changes with a descriptive message:
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

## Task 4: Pushing to GitHub

**7. Push the Changes:**
   - Push the committed changes to the GitHub repository:
     ```bash
     git push -u origin main
     ```

## Task 5: Verification

**8. Verify on GitHub:**
   - Visit your GitHub repository page and check that the `hello.txt` file is visible with the commit message "Add hello.txt with a greeting".
