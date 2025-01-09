What is Git?
Git is a distributed version control system (VCS, 版本控制系统) that is widely used for tracking changes in source code during software development. It allows multiple developers to work on a project simultaneously, manage different versions of the code, and collaborate effectively.
Key Concepts in Git:
1. Repository (Repo):
    ◦ A repository is a collection of files and directories that are tracked by Git. It can be local (on your machine) or remote (on a server like GitHub, GitLab, or Bitbucket).
2. Commit:
    ◦ A commit is a snapshot of the changes you've made to the files in the repository. Each commit has a unique identifier (hash) and a message describing the changes.
3. Branch:
    ◦ A branch is a separate line of development. The default branch is usually called main or master. You can create new branches to work on features or fixes without affecting the main codebase.
4. Merge:
    ◦ Merging is the process of combining changes from one branch into another. For example, you might merge a feature branch into the main branch when the feature is complete.
5. Pull/Push:
    ◦ Pull: Fetching changes from a remote repository and merging them into your local branch.
    ◦ Push: Sending your local commits to a remote repository.
6. Clone:
    ◦ Cloning a repository means creating a local copy of a remote repository on your machine.
7. Fork:
    ◦ Forking a repository creates a copy of the repository under your own account on a platform like GitHub. This is often used when you want to contribute to someone else's project.
8. Pull Request (PR):
    ◦ A pull request is a way to propose changes from one branch to another, often used in collaborative projects. It allows others to review your changes before they are merged.
Basic Git Commands:
• git init: Initializes a new Git repository.
• git clone <repo-url>: Clones a remote repository to your local machine.
• git add <file>: Adds changes in the working directory to the staging area.
• git commit -m "message": Commits the staged changes with a message.
• git push: Pushes local commits to a remote repository.
• git pull: Pulls changes from a remote repository to your local branch.
• git branch: Lists all branches in the repository.
• git checkout <branch-name>: Switches to a different branch.
• git merge <branch-name>: Merges changes from another branch into the current branch.
Example Workflow:
1. Clone a Repository:
git clone https://github.com/username/repo.git2. Create a New Branch:
git checkout -b feature-branch3. Make Changes and Commit:
git add .
git commit -m "Add new feature"4. Push Changes to Remote:
git push origin feature-branch5. Create a Pull Request:
    ◦ Go to the repository on GitHub and create a pull request from feature-branch to main.
6. Merge the Pull Request:
    ◦ After review, merge the pull request to main.
Git is a powerful tool that can significantly enhance your coding workflow, especially when working in teams or on open-source projects.