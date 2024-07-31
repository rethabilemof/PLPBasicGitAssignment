## Task 1: Repository Setup

### 1. GitHub Repository Creation

1. Log in to your GitHub account.
2. Create a new repository named `PLPBasicGitAssignment`.
3. Initialize the repository with a README file.

## Task 2: Local Setup

### 2. Local Folder Setup

1. Create a new folder on your local machine named `PLPBasicGitAssignment`.
2. Open a terminal or command prompt and navigate to the newly created folder:

   ```bash
   mkdir PLPBasicGitAssignment
   cd PLPBasicGitAssignment
   ```

### 3. Git Initialization

1. Initialize a new Git repository in your local folder:

   ```bash
   git init
   ```

### 4. Connecting to GitHub

1. Link your local repository to the GitHub repository you created in Task 1:

   ```bash
   git remote add origin https://github.com/rethabilemof/PLPBasicGitAssignment.git
   ```

## Task 3: Making Changes

### 5. Create a File

1. Inside your local folder, create a new text file named `hello.txt`:

   ```bash
   echo "Hello, Git!" > hello.txt
   ```

### 6. Committing Changes

1. Stage the changes:

   ```bash
   git add hello.txt
   ```

2. Commit the changes:

   ```bash
   git commit -m "Add hello.txt with a greeting"
   ```

## Task 4: Pushing to GitHub

### 7. Pushing to GitHub

1. Push the committed changes to your GitHub repository:

   ```bash
   git push -u origin main
   ```

## Task 5: Verification

### 8. Verify on GitHub

1. Visit your GitHub repository in a web browser.
2. Confirm that the `hello.txt` file and commit message are visible.
