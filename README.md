# PLPBasicGitAssignment

## Steps and Commands Used

1. **GitHub Repository Creation**:
   - Created a new repository named `PLPBasicGitAssignment` on GitHub and initialized it with a README.

2. **Local Setup**:
   - Created a local folder named `PLPBasicGitAssignment`.
   - Opened terminal and navigated to the folder:
     ```bash
     cd path/to/PLPBasicGitAssignment
     ```
   - Initialized a new Git repository:
     ```bash
     git init
     ```
   - Linked local repository to GitHub:
     ```bash
     git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git
     ```

3. **Making Changes**:
   - Created a file `hello.txt` with the content "Hello, Git!":
     ```bash
     echo "Hello, Git!" > hello.txt
     ```
   - Staged and committed the changes:
     ```bash
     git add hello.txt
     git commit -m "Add hello.txt with a greeting"
     ```

4. **Pushing to GitHub**:
   - Pushed the changes to GitHub:
     ```bash
     git push -u origin main
     ```

5. **Verification**:
   - Verified that `hello.txt` is visible on GitHub.
