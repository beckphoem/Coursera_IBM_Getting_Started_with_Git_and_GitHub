# Lesson 2.1.1 - Cloning and Forking GitHub Projects.

# Objectives

After watching this video, you will be able to:
- Clone and sync repositories
- Fork a project to make a base for a new project
- Use git commands to communicate with other developers.

# Team Working with GitHub

GitHub has over existing 100M repositories, including some very useful projects. 

Whether you are joining a team or basing your own project on prior work, some of the most powerful tools are forking and cloning a repository. 

Cloning generally refers to creating a copy of a repository on your local machine.

Cloned copies can be kept in sync between the two locations. 

Forking allows you to modify or extend a project without affecting the original project. 

Frequently, this is used to take an existing project and make it the starting point for your new project. 

- Over 100M existing repositories.

- Powerful tools include forking and cloning a repository
- Cloning creates a copy of a repository on your local machine
- Cloned copies can syns between locations
- Forking modifies or extends a project. 

# Cloning a GitHub Repository

To clone a GitHub repository, navigate to the repository that you want to clone. 

 Under the repository name, click Code in the Clone with HTTPS section, cilck the clipboard button to copy the URl to download the source code, you can click download zip, but without the version control information. 

- Navigate to the repository you want to clone

- Click Code
- In the Clone with HTTPS section, click clipboard to copy the URL
- Download source code without version control 


![alt text](image/Lesson_2_1_4/1.png)

On your local machine, open a `Terminal` window and change to the direcctory where you want to clone to be copied. 

Type 'git clone' followed by pasting the URL that you copied above and then press ENTER to execute the cloning.

- Open a Terminal window and chagne to the target directory

- Type `git clone` paste in the URL and press ENTER to execute the cloning.
![alt text](image/Lesson_2_1_4/2.png)

# Syncing Local Changes

 When you have made your changes and are ready to sync your code back to GitHub. First, you must run the `git add <files> ` command. This moves the changed files into a staging area on the GitHub repository.

 The stagin area is an area where commits can be formatted and reviewed before completing the commit .

 Next, when you are ready, run `git commit -m <message>` and this will commit changes in the staging area. 

 When you are ready to move your changes fully into the GitHub repository, Use the `git push` command. This will pushh all the commited changes into the repository.

 - To sync code back to GitHub
    - Run the `git add <file>` command
    - Changed files move to staging area
    - Next, run `git commit -m <message>` to commit changes in the staging area
- To move changes fully into the GitHub repository 
    - Use the `git push` command