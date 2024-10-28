# Lab 3.2.1 GitHub UI

# Scenario

You recently got hired as a develoer in a micro-finance startup with a mission to empower and provide opportunities for low income individuals. The core team currently uses Subversion (SVN) for managing code. They want to slowly move their code to Git. You are asked to host their sample code to calculate simple interest on GitHub in a new reposiotry as the first step in this journey. You will not only host the script, but also follow best practices introduced in this course and create supporting documents for the open source project including a code of conduct, and contribution guidelines. Additionally, the repository should be available to the community under the Apache License  2.0.

# Objectives.

After completing this lab, you would have demonstrated that you can:
1. Create a new repository in your GitHub account. 
2. Select the appropriate license for your project.
3. Create a README.md file that explains the purpose of the project.
4. Create a **Code of Conduct** markdown that explains how you want the community to behave and interact with each other.
5.  Create a **Contribution Guidelines** markdown that tells the community how to contribute.
6. Commit the new files to the repository.

> Note: Throughout this lab, you will be promted to copy and paste URLs into an editor and save it on your own device. These URLs will be uploaded for peer review in the Final Submission section of the course. You can use any editor app to keep note of your URLs.

# Task 1: Create a GitHub repository

1. Create a new GitHub repository called "github-final-project" and make sure that it is public.
2. Select the Add a README file and Choose a license check boxes. Pick `Apache 2.0 License` from the drop down.
3. Click **Create repository**. Your repository is created and includes the README and LICENSE files. Now, you are ready to update your repository files to include useful information your community.
4. Save the URL of the repository in a Notepad to submit later for peer review.

# Tasks 2: Add a license file

1. As part of Task 1, you picked a license when creating the repository.
2. Open the LICENSE.md file and check that its content are pointing to `Apache License 2.0`

# Task 3: Update the README file

1. Add the following information to the file:

```
A calculator that calculates simple interest given principal, annual rate of interest and time period in years.

Input:
    p, principal amount
    t, time period in years
    r, annual rate of interest
Output
    simple interest = p*t*r
```

Optional - You can continue to update the README file as you develop your project. You can find some ideas for useful README content from the following resources:

[GitHub README](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

[Make a README](https://www.makeareadme.com/)

[Awesome README](https://github.com/matiassingers/awesome-readme)

# Task 4: Add a code of conduct

A code of conduct helps set the ground rules for the behavior of your project's participants. It defines standards for how to engage in a community.

GitHub provides templates for common codes of conduct to help you quickly add one to your project. To add a code of conduct to your project, complete the following steps:
1. Add a new file name `CODE_OF_CONDUCT.md` to the root folder of the repository with "Contributor Covenant" template.

2. Go to your repositories homepage and check if the file has been created. 

# Task 5: Add contribution guidelines

The contribution guidelines tell project participants how to contribute to the project. To add contributions guidelines, complete the following steps:

1. Create a new named `CONTRIBUTING.md` in the root directory of the repository with the following information:

```
ALL contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome 
```

2. Optionally, you can review the following guides for examples of contribution guidelines and update this file.

[Contributing to Legit Info, a Call for Code for Racial Justice Project](https://github.com/Call-for-Code-for-Racial-Justice/Legit-Info/blob/main/CONTRIBUTING.md)

[Contributing to OpenEEW](https://github.com/openeew/openeew/blob/master/CONTRIBUTING.md)

[Contributing to Atoom](https://github.com/atom/atom/blob/master/CONTRIBUTING.md)

[How to contribute to Ruby on Rails](https://github.com/rails/rails/blob/main/CONTRIBUTING.md)

3. Commit the file into the main branch and check if it is listed on the homepage of the repository.

# Task 6: Host the script file

1. Create a new file name `simple-interest.sh` in the root directory of the repository

2. Add the following code in the new file:

```
#!/bin/bash

# THis script calculates simple interest given principal,

# annual rate of interest and time period in years. 

# Do not use this in production. Sample purpose only.

# Author: Upkak Lidder (IBM)

# Additional Authors:
# <beckphoem>

# Input:
# p, principal amount
# t, time period in years
# r, annual rate of interest

# Output:

# simple interest = p*r*t

echo "Enter the principal:"
read p
echo "enter rate of interest per year:"
read r
echo "Enter time period in years:" 
read t

s=`expr $p \* $t \* $r /100`
echo "The simple interst is: "
echo $s
```
3. Commit the file into the main branch.

# Checklist

Save your repository URL safely for use in your submission later in this course.