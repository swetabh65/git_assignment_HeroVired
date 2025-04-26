# git_assignment_HeroVired

## Q1. Calculator Plus:

a) Git repository name **git_assignment_HeroVired **is created
-> REpository git_assignment_HeroVired is created

b) Create a ‘dev’ branch and add this code.
->![image](https://github.com/user-attachments/assets/589575b3-3e8e-4e34-8bc5-f2d973b12c9b)

c) Merge this branch with the main branch and make a release of version 1 of the ‘calculator plus app’.
-> Dev branch is then merged with "Main" branch

d) Add any of your classmates as collaborators.
-> Darshit13J was added as a reviewer.

e) Implement a feature by creating a new branch called ‘feature/sqrt’. 
-> ![image](https://github.com/user-attachments/assets/5e532557-73f0-4322-9b07-5eaefbea6b1c)

f) Add the ‘sqrt’ code to it.
-> ![image](https://github.com/user-attachments/assets/4acc3504-c0bf-4757-98cc-f0e43849d433)

g) While you are working on this feature, imagine that one critical bug is reported in the main branch, and you need to switch back to the ‘dev’ branch, create fixes, and apply them while keeping your ‘feature/sqrt’ branch up-to-date. For this, you need to create
-> Switched back to "Dev" branch after putting the changes in feature/sqrt branch as a stash

h) After completing the feature implementation and ensuring that the application works correctly, create a pull request targeting the main branch.
-> Pull request is raised in terminal with command git pull .

i) Request a code review from a team member and make any necessary improvements based on the review feedback.
-> Darshit13J was a code reviewer

j) Once the code reviewer approves your pull request, merge the "feature/sqrt" branch into the ‘dev’ branch.
-> feature/sqrt branch is now merged into the dev branch after successful review and approval of code from Darshit13j

k) Finally, do the testing in the ‘dev’ branch itself and merge it into the ‘main’ branch and create a ‘version 2’ release.
-> Testing is performed successfully and then code is  merged to main branch with Version2 release.


## Q2. For a project that deals with large binary files, integrate Git LFS (Large File Storage) to handle these files efficiently. Demonstrate how to add, commit, and push binary files to the repository, ensuring they are tracked by Git LFS correctly. Clone the repository on another machine to verify that the binary files are downloaded correctly.

a) In the repository ‘git_assignment_HeroVired’, create a branch ‘lfs’. Upload any large file whose size is over ‘200mb’ and try to push this file into the repository.
-> ![image](https://github.com/user-attachments/assets/7daab49b-1881-454e-9703-67089d582e3e)


## Q3. In this same GitHub repository, create a new branch ‘geometry-calculator’, we'll work on a simple Python program that calculates the area of a circle and the area of a rectangle. We'll use Git stash to switch between working on multiple features (calculating circle area and calculating rectangle area) without committing incomplete changes.

a) Create a New Branch:
-> ![image](https://github.com/user-attachments/assets/d6c614c0-4655-4188-84fa-f868a5a9c8fc)

b) Stash Changes for Circle Area Feature:
-> git stash -u was used to stash the changes as the code was untracked.

c) Create a New Branch for Rectangle Area Feature
-> ![image](https://github.com/user-attachments/assets/8d28b06c-473f-4e85-b4ca-94b32e89f4d0)

d) Stash Changes for Rectangle Area Feature
-> git stash was used to stash the changes as the code was added with git add .

e) Switch Back to Circle Area Branch
-> ![image](https://github.com/user-attachments/assets/68a3cfa4-076e-4004-85e3-9ff33ce33b79)

f) Commit and Push Circle Area Feature
-> git stash apply "stash@{0}" was used to apply the changes followed by git add, commit and push commands.

g) Switch Back to Rectangle Area Branch
-> ![image](https://github.com/user-attachments/assets/de712354-6717-4cda-bcd0-218d9a4664a2)
And then git stahs apply "stash@{1}" followed by commit and push commands. 

i) Create Pull Requests
-> Pull request is then made for both feature/rectangle-area and feature/circle-area branch

j) Review and Merge
-> Review request is made to Darshit13J for merging the changes to Main branch and then it is moved after successful approval.

## After submition of project, visibility is now channged from Private to Public.












