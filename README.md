Git Workflow Project

Project Overview

This project is a hands-on practice of common Git workflows used in real software projects.

The project covers:

- Git commits
- Git revert
- Git reset
- Git restore
- Branching
- Merging
- Branch cleanup
- GitHub repository management
- Project documentation

Git Workflow Exercises

Step 14 — Create a Temporary Commit

A temporary feature was added to "task-manager.txt" and committed to Git.

"Temporary Commit" (screens/14-temporary-commit.png)

Step 15 — Revert a Commit

The temporary commit was safely undone using "git revert".

"Git Revert" (screens/15-git-revert-commit.png)

Step 16 — Check Git Status

The working tree was checked to confirm there were no outstanding changes.

"Clean Git Status" (screens/16-git-status-clean.png)

Step 17 — Create a Commit for Reset Practice

A new commit was created specifically to practice Git reset.

"Reset Practice Commit" (screens/17-reset-practice-commit.png)

Step 18 — Git Reset Soft

"git reset --soft HEAD~1" was used to undo the latest commit while keeping the changes staged.

"Git Reset Soft" (screens/18-git-reset-soft.png)

Step 19 — Unstage Changes

"git reset" was used to remove the changes from the staging area.

"Git Reset Unstaged" (screens/19-git-reset-unstaged.png)

Step 20 — Git Restore

"git restore" was used to discard the uncommitted change.

"Git Restore" (screens/20-git-restore-clean.png)

Step 21 — View Git History

The Git history was viewed using the graph format.

"Git History" (screens/21-final-git-history.png)

Step 22 — Create a Feature Branch

A separate branch called "feature/notifications" was created.

"New Branch" (screens/22-new-branch.png)

Step 23 — Add a Notification Feature

A notification feature was added to the project on the feature branch.

"Notification Feature" (screens/23-notification-feature.png)

Step 24 — Commit the Feature

The notification feature was committed to the feature branch.

"Notification Commit" (screens/24-notification-commit.png)

Step 25 — Switch to Master

The project was switched back to the "master" branch.

"Switch to Master" (screens/25-switch-to-master.png)

Step 26 — Merge the Feature

The "feature/notifications" branch was merged into "master".

"Merge Notifications" (screens/26-merge-notifications.png)

Step 27 — Verify the Merge

The project was checked to confirm that the notification feature was present after the merge.

"Merge Verification" (screens/27-merge-verification.png)

Step 28 — Delete the Feature Branch

After the merge, the feature branch was deleted because it was no longer needed.

"Delete Feature Branch" (screens/28-delete-feature-branch.png)

Step 29 — Final Git Check

The final Git status and history were checked.

"Final Git Check" (screens/29-final-git-check.png)

GitHub Setup

Step 30 — Create the GitHub Repository

A GitHub repository named "git-workflow-project" was created.

Step 31 — Connect the Local Repository

The local Git project was connected to the GitHub repository using a remote named "origin".

"GitHub Remote" (screens/31-github-remote.png)

Step 32 — Push the Project

The local project was pushed to GitHub.

"GitHub Push" (screens/32-github-push.png)

Step 33 — Verify the GitHub Repository

The project was checked on GitHub after the push.

"GitHub Repository" (screens/33-github-repository.png)

Project Structure

git-workflow-project/
│
├── task-manager.txt
├── README.md
└── screens/
    ├── 14-temporary-commit.png
    ├── 15-git-revert-commit.png
    ├── 16-git-status-clean.png
    ├── 17-reset-practice-commit.png
    ├── 18-git-reset-soft.png
    ├── 19-git-reset-unstaged.png
    ├── 20-git-restore-clean.png
    ├── 21-final-git-history.png
    ├── 22-new-branch.png
    ├── 23-notification-feature.png
    ├── 24-notification-commit.png
    ├── 25-switch-to-master.png
    ├── 26-merge-notifications.png
    ├── 27-merge-verification.png
    ├── 28-delete-feature-branch.png
    ├── 29-final-git-check.png
    ├── 31-github-remote.png
├── 32-github-push.png
    └── 33-github-repository.png

What I Practiced

By completing this project, I practiced:

- Creating and managing Git commits
- Reverting previous commits
- Using "git reset"
- Using "git restore"
- Creating and switching branches
- Merging feature branches
- Deleting merged branches
- Viewing Git history
- Connecting a local repository to GitHub
- Pushing a project to GitHub
- Documenting a project with Markdown
- Organizing project screenshots

Tools Used

- Git
- GitHub
- Ubuntu/WSL
- Nano
