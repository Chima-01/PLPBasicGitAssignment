# How to add a repository locally to github

## GitHub Repository Creation:

 - Log in to your GitHub account.

 - Create a new repository on GitHub call it "PLPBasicGitAssignment"

 - Don't Initialize it with a README file as it can cause merge conflict later.

## Local repo setup

 - Open a terminal or command prompt and navigate to the created folder.
 - Create a new folder on your local machine use the command ``` mkdir PLPBasicGitAssignment ```.
 - change directory to PLPBasicGitAssignment.
 - Initialize to a git repo using this command ``` git init ```
 - use this command ``` git remote add origin <repository-url> ``` to link the local repository to the GitHub repository
 - create file named "hello.txt" use the "touch" command
 - git add hello.txt
 - git commit hello.txt with a message. for instance ``` git commit -m "my first commit" ```
 - Then push to the remote repo using this command ``` git push -u origin main ```

## Incase of a merge conflict follow the instructions below:
 - Execute the following command to merge the branches while allowing unrelated histories:
 ``` git merge --allow-unrelated-histories origin/main ```

 - commit the merge
 ``` git commit -m "Merging coflicts" ```

 - Then push
 ``` git push origin main ```
