Lab 4 Notes

Q1
--global means the Git configuration applies to all repositories for my user account on this computer. If I leave it out, the configuration applies only to the current repository.

Q2
.git appeared in ls -a but not in ls. It contains Git's internal data, including the repository's history and configuration.

Q3
Git offers to track the files and folders shown under "Untracked files." There may also be thousands of .venv/ files because the virtual environment contains many files.

Q4
After adding .gitignore, files inside .venv/, __pycache__/, and matching .pyc files disappear from git status. Git now ignores them.

Q5
Yes, .gitignore should be committed because it tells Git which files to ignore. Other people using the repository need these rules too.

Q6
README.md moves from "Changes not staged for commit" to "Changes to be committed." This means its changes moved from the working tree to the staging area.

Q7
Git prints the new commit ID and a summary of the changes, including files changed and insertions/deletions. The number of changed files depends on what was committed.

Q8
The first seven characters are the short version of the commit hash. They are used to identify that specific commit.

Q9
The four steps are edit, check the changes, stage with git add, and commit with git commit. Then the cycle repeats for the next change.

Q10
README.md gets a special name because GitHub automatically displays it on the repository's front page. It gives visitors an overview of the project.

Q11
gh auth login connects the GitHub CLI to my GitHub account and saves the authentication. This lets me push without entering my password each time.

Q12
README.md appears on the GitHub repository's front page. GitHub automatically renders it because it is named README.md.

Q13
No, pushing does not change my local history. It only copies my local commits to the GitHub repository.

Q14
A private repository exists on GitHub but is only accessible to people with permission. If a repository doesn't exist on GitHub, there is no remote repository to access.