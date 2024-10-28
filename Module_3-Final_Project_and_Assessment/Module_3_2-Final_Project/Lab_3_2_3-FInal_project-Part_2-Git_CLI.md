# Scenario 

Congratulations on starting the journey with your company by creating an open-source Simple Interest Calculator bash script on GitHub. Your changes have been accepted and merged and the company has created a new global repository for the teams to collaborate. Other developers have contributed to this repository over time. Your teams has found a mistake in one of the markdown files. You are asked to fork this repository and fix the mistake using Git GLI in the provided lab environment and open a pull request (PR).

# Objectives 

After completing this lab, you will be able to demonstrate that you can:

1. Fork the upstream repository into your own account.
2. Clone the code locally in the lab environment.
3. Create a branch in the repository.
4. Make changes in the branch and commit it.
5. Merge the branch back into the `main` branch
6. Create a Pull Request from the forked repository to the upstream repository. 
7. Revert a chagne that you made earlier. 

> Note: Throughout this lab, you will be prompted to copy and paste URLs into a notepad and save the notepad on your own device. These URLs will be uploaded for peer review in Final Submission section of the course. You can use any notepad app to keep note of your URLs.

# Task 1: Fork the repository

1. Fork the project's [source repository](https://github.com/ibm-developer-skills-network/jbbmo-Introduction-to-Git-and-GitHub)

2. Save the URl of your foked repository in a notepad to submit later for peer review.

# Task 2: Fix the typo and merge with main

1. Clone the forked repository in the lab environment.

2. Create a branch named `bug-fix-typo`

3. Change the footer in the main `README.md` file from
```
2022 XYZ, Inc.
```
to 
```
2023 XYZ, Inc.
```

4. Add the file with you fix and commit it with a meaningful message.

5. Push your fix to the `bug-fix-typo` bracnh. In this step, you will ned to generate a personal access token from GitHub.com to use as your password. Follow the intructions in the lab [Generate GitHub persional access token](/Module_2-Git_Commands_and_Managing_GitHub_Projects/Module_2_1-Git_Workflows_with_Git_Commands/Lab_2_1_0-Generate_personal_access_token.md)
6. Switch to the main branch. Merge the  `bug-fix-typo` branch back into your `main` branch. Take a screenshot showing the current branch and successful merge operation with the file that has changed. Save the screenshot as `merge_branches.pgn` or `merge_branches.jpg`

# Task 3: Revert the typo and submit a pull request.

1. Check the content of README.md in the main branch. The file should now read:
```
2023 XYZ, Inc.
```
2. Create a new branch named `bug-fix-revert`

3. Revert back the change you implemented in the previous task using the `git revert` command. The file should now read:
```
2022 XYZ, inc
```

4. Push the revert to your repository in the `bug-fix-revert` branch. Please ensure you use the personal access token that you generated on GitHub for your account as the password (and not your actual git password) when prompted.

5. Go to the Github Ui. Creaet a new pull request from the `bug-fix-revert` branch of your repository to the `main` branch of the [original repository](https://github.com/ibm-developer-skills-network/jbbmo-Introduction-to-Git-and-GitHub). Thi PR will be closed automaticlly. Note the URL of this PR in a notepad to submit later for peer review 

# Task 4: Check the status of your branches.

1. Navigate to the `Branches` section within the GitHub UI on your page. It will be in the following format:
```
https://github.com/<Your Github username>/jbbmo-Introduction-to-Git-and-GitHub/branches
```
2. Within this section, you will find the branch names along with their current status.

3. Make a note of URL of this page in a notepad to submit during peer review.

# Checklist

After completing this part of the final project, you should have:

1. The forked repository URL.
2. The pull request URl.
3. The screenshot showing the merge operation of `bug-fix-typo` into `main` named `merge_branches` in pgn of jpg format.

4. The URL of the `Branches` page showing the branches of the repository and their status.

# Summary

Congratulations! You have completed both parts of the final project. You have demonstarted that you know how to create ean open-source project in Git, make changes to that project, and make it available to the community. You can fork a GitHub repository, clone it to your local system, make changes to the local repository, commit the changes locally, push it back to your GitHub fork, and create a pull request to add your update to the original repository.
