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
