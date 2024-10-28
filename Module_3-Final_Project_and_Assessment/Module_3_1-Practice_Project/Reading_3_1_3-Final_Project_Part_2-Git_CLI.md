# Final Project Git CLI

# Scenario

Your changes have been accepted and merged and the company has created a new global [repository](https://github.com/ibm-developer-skills-network/jbbmo-Introduction-to-Git-and-GitHub) for the teams to collaborate. Other developers have contributed to this repostiory over time. Your team has found a mistake in one of the markdown files. You are asked to fork this repository and fix the mistake using Git CLI in the provided lab environment and open a pull request (PR).

# Objectives

After completing this lab, you will be able to demonstrate that you can : 

1. Fork the upstream repository into your own account.

2. Clone the code locally in the lab environment.

3. Create a branch in the repository.

4. Make chagnes in the branch and commit it.

5. Merge the branch back into the `main` branch.

6. Create a Pull Request from the forked repository to the upstream repository.

7. Revert a change that you made earlier. 

> Note: Throughout this lab, you will be prompted to copy and paste URLs into a notepad and save the notepad on your own device. These URLs will be uploaded for peer review in the Final Submission section of the course. You can use any notepad app to keep note your URLs.

# Task 1: Fork the repository

1. Fork the project's [source repository](https://github.com/ibm-developer-skills-network/jbbmo-Introduction-to-Git-and-GitHub).

2. Save the URL of your foked repository in a notepad to submit later for peer review.

# Task 2: Fix the typo and merge with main

1. Clone the forked repository in the lab environment. 

2. Create a branch named `bug-fix-typo`

3. Change the footer in the main README.md file from

```
2022 XYZ, Inc.
```
to
```
2023 XYZ, Inc.
```

4. Add the file with your fix and commit it with a meaningful message.

5. Push your fix to the `bug-fix-typo` branch. In this step, you will need to generate to personal access token from GitHub.com to use as your password. Follow the instructions in the lab [Generate GitHub personal access token](/Module_2-Git_Commands_and_Managing_GitHub_Projects/Module_2_1-Git_Workflows_with_Git_Commands/Lab_2_1_0-Generate_personal_access_token.md)