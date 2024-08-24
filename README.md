# Git Assignment - <nlyca22>

a. What is an issue?
In GitHub, an "issue" is a way to track issues, tasks, bugs, enhancement, or any type of work that we want to track for a project. It allows our team-mates or colleagues to collaborate on work. Issues can also be labeled, assigned to team-members, linked to specific milestones, or pull requests. 

b. What is a "pull request"?
In Github, a "pull request" is a maker-checker process. When I "pull a request", I am proposing changes to a GitHub repository and asking someone to review and merge them into the repository's main codebase. Whoever that reviews my proposed changes can comment on it. A "pull request" can also be linked to an "issue" (see point a). 


c. Describe the steps to open a pull request?
Preliminary steps: 
Step 1: Create a new branch for my changes
Step 2. Commit the changes to my new branch
Step 3. Push the branch to the GitHub repository

Steps to open a Pull Request: 
Step 1: Go to the repository on Github
Step 2: Click the "Pull requests" tab
Step 3: Click the "New pull request" button
Step 4: Select the branch I've made changes to, and the branch I want to merge into (usually main branch)
Step 5: Add a TITLE and DESCRIPTION for my pull request
Step 6: Click "Create pull request."
Step 7: Review and Merge: The repository owner (myself) or collaborators will review this "pull request". If everything is good, the "pull request" will be successfully merged into the base (main) branch.


d. Describe the steps to add a collaborator to a repository (share write permissions)
Step 1: Navigate to the repository on Github where I want to add a collaborator
Step 2: Click on "Settings" tab top of the repository page
Step 3: In the "Settings, on the left hand side, click on "Collaborators"  
Step 4: Under Manage Access, click on "Add people" 
Step 5: Enter the GitHub username(s) or email(s) of the person(s) I want to add
Step 7: Click "Add" to send the invitation. Note: The invited user(s) will receive a notification and must accept the invitation to gain access.


e. What is the difference between git and GitHub?
Git: Git is a tool that I use locally on my laptop to manage my code. It allows me to track changes in my code over time, lets me manage my project’s history, and collaborate with others.  

GitHub: GitHub is a cloud-based hosting service that allows me to store, manage, and collaborate on Git repositories. GitHub provides a web interface for Git. It has features like issue tracking, pull requests, and project management tools. It is where I can share my Git repositories with others and work together on projects.  

f. What does "git diff" do?
The "git diff" command shows the differences between 2 states of a Git repository, it compares changes that haven't been staged. 
As for "git diff --staged" or "git diff --cached": it compares changes between the staged area and the last commit. 
It also compares differences between any 2 commits or branches. 

It's useful for reviewing what changes have been made before committing them.


g. What is the "main branch"?
The "main branch" is the DEFAULT branch in a Git repository where the stable version of the project’s code is typically maintained. 
It’s the branch where my final product or latest stable version of the project lives. 
Changes are usually merged into the "main branch" only after they've been tested and reviewed.


h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, we should generally avoid pushing changes directly to the main branch, especially in collaborative projects. 
Instead, we should create a new branch for our changes and then merge them back into the main branch through a pull request. (This approach allows for code review and testing, ensuring that the main branch remains stable and free of bugs.)