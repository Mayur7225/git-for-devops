GIT COMMANDS
1. Repository Initialization
Command: git init
Purpose: Initializes a new Git repository in the current directory.
Result: Created a new Git repository inside the git-for-devops directory.
2. File Creation
Command: touch nibba.txt nibbi.txt
Purpose: Created two text files, nibba.txt and nibbi.txt.
Result: Empty files created in the repository.
3. Git Status
Command: git status
Purpose: Shows the current status of the repository, such as staged, modified, or untracked files.
Result: Revealed that nibba.txt and nibbi.txt were new files and staged for commit.
4. Staging Files
Commands: git add nibbi.txt, git add nibba.txt
Purpose: Staged the nibbi.txt and nibba.txt files for commit.
Result: The files were ready to be committed to the Git repository.
5. Git Configuration
Commands: git config --global user.name "mayur722", git config --global user.email "mayuraware7225@gmail.com"
Purpose: Set up your global Git username and email to ensure correct author information is included in commits.
Result: Your Git identity was configured globally across repositories.
6. First Commit
Command: git commit -m "Initial commit"
Purpose: Made the first commit with a message "Initial commit".
Result: Created the first commit in the repository, which included the staged files (nibba.txt and nibbi.txt).
7. Branch Management
Commands:
git checkout -b dev — Created and switched to a new dev branch.
git checkout master — Switched back to the master branch.
git checkout dev — Returned to the dev branch.
Purpose: These commands were used to create and switch between branches for feature development or experimentation.
8. Additional Commit
Commands: git commit -m "added nibba changes", git commit -m "added nibbu"
Purpose: Made additional commits with descriptive messages about the changes made to nibba.txt and nibbu.txt.
Result: These commits tracked further changes in the repository.
9. Viewing Commit History
Commands: git log, git log --oneline
Purpose: Displayed the commit history.
Result: Used git log to view detailed commit history and git log --oneline for a condensed view of the logs.
10. Miscellaneous Commands
Commands: clear, ls, git branch
Purpose: These were used for clearing the terminal, listing directory contents, and checking which branches are available in the repository.
Result: Helped maintain the terminal session and managed the local branches.
