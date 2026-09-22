# A02


This tutorial provides guide on how to set up Github


Step 1: Install the  Software
download these tools: 
Git
VS Code

Step 2: Set Up Git Globally
Open your terminal if you have mac or Command Prompt/Git Bash for a windows and configure your identity:
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

step 3: Open Your Project in VScode
1. Open Vscode
2. Select File > Open Folder and choose the directory where you want to keep your project.
3. Open the built-in terminal in Vscode by selecting Terminal > New Terminal

Step 4: Clone Your GitHub Repository
1. Copy your repository URL from GitHub
2. Run the command in VScode terminal:
   ```bash
   git clone https://github.com
   ```
3. Navigate into the cloned folder:
   ```bash
   cd A02
   ```

Step 5: Make Changes and Save (Commit)
1. Open or create the README.md file inside VScode
2. Edit the document or add content.
3. Stage your changes by tracking them:
   ```bash
   git add README.md
   ```
4. Commit the changes locally with a clear message:
   ```bash
   git commit -m "Feature: added workflow for using github"
   ```

Step 6: Push to GitHub
Upload your local commits back up to the cloud:
```bash
git push origin main
```

---

Glossary of Terms

Branch: A parallel version of a repository that diverges from the main working project, allowing you to make changes without affecting the primary source code.
Clone: A full duplicate copy of a remote target repository downloaded locally onto your computer.
Commit: A recorded snapshot of changes made to your files, saved locally to the Git history timeline.
Fetch: A command that downloads new changes, commits, and refs from a remote repository without integrating them into your local workspace.
GIT: A local, decentralized version control system designed to track file changes across a development project.
Github: A cloud-based hosting service and platform designed to store Git repositories and facilitate collaborative development.
Merge: The process of combining independent history paths and code timelines from two different branches into a single branch.
Merge Conflict**: A disruptive event that occurs when Git cannot automatically merge code changes because two developers modified the exact same line of code independently.
Push: The command used to upload your locally committed timeline updates and file changes to a remote repository server.
Pull: A combined Git action that fetches updates from a remote server and immediately merges them directly into your current local branch.
Remote: The version of your project repository hosted online or on a separate network server (like GitHub) rather than your local machine.
Repository: The foundational data folder structure where Git tracks your project's historical logs, version branches, and file states.

