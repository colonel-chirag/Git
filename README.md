# Git
Detailed Description of GIT

Introduction: What is GIT?
Git is a free and open-source distributed version control system, which is designed to handle everything from small to very large projects with speed and efficiency.

So Why Git? What are the advantages?
Imagine a scenario without using Git.

There is a large project and 100 developers are working on the project.


Developers used to submit their codes to the central server without having a copy of their own.
Any changes made to the source code were not known to the other developers.
There was no communication between any of the developers.
Now, let's analyse the scenario after using Git.


Every developer has an entire copy of the code on their local system.
Any change made to the source code can be tracked by others.
There is regular communication between the developers.
Therefore, for large projects that involve thousands of developers, Git helps those developers to work collaboratively and efficiently in a structured manner. Learn More.
![image](https://user-images.githubusercontent.com/59536110/175824209-b187560e-0d11-4c44-881e-d4e7242133ec.png)

Learn GIT: Basics to Advanced Concepts
1. Uses of Git
Git is used to tracking changes in the source code.
Distributed version control tool used for source code management.
Allows multiple developers to work together.
Supports non-linear development because of its thousands of parallel branches.
2. Features of Git
Free and open-source
Tracks history
Supports non-linear development
Creates backup
Scalable
Supports collaboration
Branching is easier
Distributed development.
3. Git WorkFlow
The following image shows the git workflow diagram:


In Git, the workflow is mainly divided into three areas -

Working directory - This is the area where you modify your existing files.
Staging area (Index) - In this, the files in your working directory are staged and snapshots are added.
Git directory or repository - It is basically where you perform all the changes that need to be made i.e. perform commits to branch, checkout branch, make changes etc.
![image](https://user-images.githubusercontent.com/59536110/175824377-5347f105-c1b5-4588-96e6-aba7ee856442.png)
4. Install Git: Installation in Windows/Linux/Mac OS X
Install Git on Windows -

Download the latest version of Git from here.
After starting the installer, follow the command on the screen and press Next to complete the installation.
Open Command Prompt and run the following command to configure Git on your PC using your username and email.
$ git config --global user.name "username" 
$ git config --global user.email "user_emails@interviewbit.com"
This configures Git on your PC with your username and email.

Install Git on Linux -

You can install Git on Linux using the command apt-get :
$ sudo apt-get update
$ sudo apt-get install git
Configure your username and email using the following command:
$ git config --global user.name "user_name"
$ git config --global user.email "user_email@interviewbit.com"
Install Git on Mac OS -

Download the latest version of Git from here.
Open the installer and follow the instructions.
Now since Git is installed, open command line and configure your username and user email.
$ git config --global user.name "user_name"
$ git config --global user.email "user_email@interviewbit.com"
5. Git Clone
git clone is a command which is used to clone or copy a target repository.

The following image shows an illustration of the git clone command. Using the command, a copy
![image](https://user-images.githubusercontent.com/59536110/175824466-251792d9-82fc-49a4-b855-13b6743ec67e.png)
How to clone a repository?

Open Github and navigate to the target repository which needs to be cloned.
Under the repo name, click on the tab Clone or Download.
An option named Clone with HTTPS appears.
Copy the Clone URL.
Open a command line and use the command: git clone <repo_URL>
In this way, a clone of the target repository can be made.

Clone a specific branch from the repository.

A very useful feature of the git clone is that it allows cloning a specific branch of the target repository without having to clone the entire repository.
To clone a specific branch, you need to use the command -b to specify the branch. The following command is used:

git clone -b <Branch_name> <Repo_URL>
6. Git Branch
A branch in Git is used to keep your changes until they are ready.
You can do your work on a branch while the main branch(main) remains stable. After you are done with your work, you can merge it to the main branch.
For creating a new branch, the following command is used :

git branch <branch_name>
For example -

git branch demo
This command creates a new branch named demo from the Main branch:
![image](https://user-images.githubusercontent.com/59536110/175824512-db344463-609a-419b-abaf-78fc78d69a61.png)
The diagram shows there is the main branch.
There are two more branches small feature and large feature working separately.
Once the work is complete for the two separate branches, you can merge it into the main branch.
7. Git Switch Branch
Using the git checkout command, we can switch from one branch to another.

Command :

git checkout <branch_name>
8. Create Remote Branches
Git doesn’t allow creating a new and isolated branch on a remote repository. But, you to make a branch remote, we can push an existing local branch.

The steps to create a remote branch is as follows:

Create a local branch and switch to that branch:
git checkout -b <branch_name>
Push in the local branch:
git push -u origin <branch_name>
Note: origin is the default name of remote
Now, if someone wants to fetch some information, one can simply run:

git fetch
git checkout <branch_name>
9. Delete Branches
Once the work is done on a branch and merged with the Main branch, one can delete the branch.

The following command is used to delete branches:

git delete -d <branch_name>
Note: This command deletes a copy of the branch, but the original branch can still exist in remote repositories.
To delete remote branches, use the following command:

git push origin --delete <branch_name>
10. Git Checkout
The Git checkout is used to command Git on which branch changes have to be made. Checkout is simply used to change branches in repositories. It can also be used to restore files.

The following image describes the scenario of creating different branches and switching to a brach when needed, i.e. we can switch from the main brach to a different branch and vice versa.
![image](https://user-images.githubusercontent.com/59536110/175824711-1472053a-d40a-4859-8981-70d755e1a196.png)

Git Checkout Branch
To checkout or create a branch, the following command can be used:

git checkout -b  <branch_name>
This will simply switch to the new branch branch_name.

Git Checkout Tag
While working on a large codebase, it because easy to have some reference point. That is where the checkout tag is used.

The following command is used to specify the tagname as well as the branch that will be checked out.

git checkout tag</tag> <branch_name>
11. GIT Status
git status is mainly used to display the state of the staging area and the repository. It helps us to track all the changes made, point out untracked files.

Command:

git status
git status after a file is added

Add files to the repo using the following command:
touch file.txt
Execute git status.
A message would be displayed, describing the changes done to the repository.
git status after a file is deleted after commit

Delete the file using the following command:
git rm file.txt
Execute git status.
A message would be displayed, describing the file has been deleted.
12. Git Commit
Git commit is used to record all the changes in the repository. The git commit will commit all the changes and make a commit-id for the same for tracking down the changes made as shown in the image below.

As shown in the image, the command git commit creates a commit-id to track down changes and commits all the changes to the git repository.
![image](https://user-images.githubusercontent.com/59536110/175998865-da1c5c77-3ca0-4537-883a-f8575ee334ad.png)
