# Version Control

Version control allows for the tracking, coordinating and managing changes to source code. Version control systems are software tools that help software teams manage, collaborate and track changes to source code over time.



# GIT 

Git is a version control system (VCS), which is a software tool that helps developers manage, collaborate and track changes to source code.



# PROCESS FOR COMMITING NEW PROJECT TO GITHUB

1. Create a new repository on GitHub.com. The repository 	should have the same name as the one on your local 	machine.


2. Open Git Bash.


3. Change the current working directory to your local 	project.


4. Use the "init" command to initialize the local directory 	as a Git repository.


5. Add the files in your new local repository. This stages 	them for the first commit.

$ git add .
Adds the files in the local repository and stages them for commit. 


6. Commit the files that you've staged in your local 	repository.

$ git commit -m "First commit"
Commits the tracked changes and prepares them to be pushed to a remote repository. 


7. At the top of your repository on GitHub.com's Quick Setup 	page, click the copy icon to copy the remote repository URL.
Copy remote repository URL field


8. In the git bash, add the URL for the remote repository where your local repository will be pushed.

$ git remote add origin <REMOTE_URL>
Sets the new remote
$ git remote -v
Verifies the new remote URL


9. Push the changes in your local repository to GitHub.com.
$ git push origin main
Pushes the changes in your local repository up to the remote repository you specified as the origin