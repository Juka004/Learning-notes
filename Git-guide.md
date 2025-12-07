
# Introduction to Git – Git for Beginners: Basic Commands & Tips

## Introduction to Git

Git is a version control system that lets you track changes in your files and collaborate efficiently with others.

1. **Basic Commands and Checks**

- `git init`  
  Initializes a local Git repository in your folder.

- `git clone <url>`  
  Downloads a remote repository to your machine.

- `git status`  
  Shows modified, added, or untracked files.

- `git add <file>` or `git add .`  
  Stages files for commit.

- `git commit -m "message"`  
  Records changes locally with a clear message.

- `git push`  
  Sends your commits to the remote repository (e.g., GitHub).

- `git pull`  
  Fetches updates from the remote repository.

2. **Common Issue Troubleshooting**

- *Error*: `src refspec main does not match any`  
  *Cause*: No commit made before pushing.  
  
  *Solution*: Make a commit before pushing.

- *Error*: `fatal: not a git repository`  
  *Cause*: You’re not inside a Git repository folder.  
  *Solution*: Make sure you initialized the folder with Git (`git init`).

- *Merge Conflicts*  
  Occur when two branches modify the same part of a file. You need to resolve the conflict manually, then commit.

3. **Practical Tips**

- Always check your repo status with `git status` before adding or committing.  
- Write short but clear commit messages.  
- Commit frequently to track progress easily.  
- Use branches to develop new features.

---

4. **Useful Resources**

- Official documentation: https://git-scm.com/doc  
- Video tutorials: search “Git basics” on YouTube  
- Interactive guide: https://learngitbranching.js.org/

*Git notes file.*

This file is available on GitHub: [Juka004/Learning-notes](https://github.com/Juka004/learning-notes)