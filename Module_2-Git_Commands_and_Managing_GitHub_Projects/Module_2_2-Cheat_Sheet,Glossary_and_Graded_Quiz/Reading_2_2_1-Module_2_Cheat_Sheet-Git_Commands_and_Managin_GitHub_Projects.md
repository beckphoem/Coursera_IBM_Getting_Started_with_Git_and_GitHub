# Reading 2.2.1 Module 2 Cheat Sheet: Git Commands and Managing GitHub Projects

|Package/Method|Description|Code Example|
|---|---|---|
|git add| Used to move changes from the working directory to the staging area| ``` git add sample.md ```|
|git add .| Allows to move the chagned files into the staging area on GitHub repositories| `git add . `|
|git am| Used to apply patches emailed to the repository| `git am < patchfile.path`|
|git branch| Allow to create an isolated environment within the repository to make changes | `git branch <new-branch>`|
|git checkout | Allows to see and change existing branches | `git checkout <existing-branch>`|
|git checkout main| Allows to switch to the main branch| `git checkout main`|
|git clone| Allows to create a copy of the remote repository| `git clone <repository-url>`|
|git commit| Allows you to take staged snapshots if changes and commit them to the project| `git commit -m "Your commit message here"`|
|git config --global user.enaml| Example 1: Sets a golbal email configuration for Git <br> Example 2: Sets a global username configuration for Git| Example 1: `git config --global user.name "your.email@example.com"` <br> Example 2: `git config --global user.name "Your name"`|
