# Reading 2.1.2 - Summary: Git Workflows with Git Commands

In this module, you learned that:

- GitHub has over 100 million repositories. You can clone a repository and sync changes back to the original. You can also fork a repository and use it as the base for the new project or work on that the project independently.

- The steps included in a GitHub workflow are:
    - Clone the remote repository or initialize a Git repository
    - Move files to a staging area
    - Perform an initial commit
    - Create a branch and work on it.
    - Add files to the staging area and commit.
    - Push local commits to the remote repository.
    - Create a pull request for review and mergin.
    - Use the pull operation to update the local repository.

- Multiple roles are involved in managing a project: Developer, Integrator, and Repository Administrator.
    - A Developer working in a group project uses commands like git clone, git pull, git fetch, git push, and git request-pull in addition to the ones needed by a standalone developer.

    - An intergrator in a group project reviews and integrates changes made by others. Integrators use commands like git pull, git revert, and git push in addition to the ones needed by participants.
    - Repostitory Administrators structure how the repository is organized and how users interact with the repository. They also configure the servers needed for accesig the web services and documentation, define email and index settings, and manage the look and feel of the application.

- The following table shows various Git commands:

| | | | | |
|---|---|---|---|---|
|git init|git checkout|git revert| git-format-patch|git fetch upstream| 
|git status|git merge|git config --global user.email| git-request-pull|git merge upstream/main|
|git add .| git clone | git config --global user.name| git-send-email| git pull upstream|
|git commit| git pull| git remote -v| git-am|git web|
|git log | git push | git remote rename| git-daemon| git-instaweb|
|git reset |git version| git remote add origin| git remote -v| git-pull downstream|
|git branch| git diff| git-remote| git remote add upstream| git-rerere|