# Creation of Git repository for ITE1100 Tutorial #4

Name: Saudia Ishmeal

Collaborator: Stephan Sewpersaud

The purpose of creating this respository was to familiarize the student with the Git and GitHub interface. This is a step-by-step outline of the actions taken to create a respository, to engage a collaborator, add branches, a name.py file, commit the file then push the branch to Github. After which a PR request will be made, approved by the collaborator then the created branch will be merged into the main (master) branch.

Steps followed: 
  1. Creation of a GitHub account and downloading Git software.
  2. Create a repository in Github and add classmate as a Collaborator on GitHub repository.
  3. Create local Git repository using Git Bash (Software).

    mkdir <given-name> (mkdir means make directory and this is simply creating the folder on your local computer. Name the directory accoringly. No spaces. Use underscore or dash in place of a space if necessary.)
     
     cd <given-name> (cd means change directory, or 'go-to' directory.)
     
  4. Initialize Commit.

    git init (This initializes the local repository you made.)

  6. Link the local respository to the respository in Github.

    git remote add origin https://github.com/user-name/repository-name.git (You can get the link by going to your created github respository then clicking the green button that says <Code>.)
     You can validate it has been linked by running the command git remote -v

  7. Create new branch in repository.
    
    git checkout -b <branch-name> (Like the directory, the branch should be named appropriately.)
     
  8. Create a new name.py or file. (If needed.)

    echo "print(' My name is...')" > name.py
      
  9. Add name.py file to  repository.

    git add name.py  (This command is used to add any file for the respository)
     
  10. After adding a file, you must commit the file.
     
    git commit -m "intended message" (Within the quotes you can make any comment/leave a message for your collaborators regarding the added file.)
    
  11. Push the created branch to GitHub.

    git push -u origin <branch-name> 
    
  12. Open Github > Respository > Branches.
  13. Create Pull Request (PR) by clicking green _"Compare & pull request"_ button.
  14. Add Collaborator as Reviewer and wait for approvals.
  15. Once approved, merge created branch into the main (master) branch by clicking the purple _"Merge Pull Request"_ button.
  16. On the main respositiory page, click _Add a README.md_ and in the description section outline the details of the steps taken.

To complete these tasks, further guidance along each step was referenced from the Hubspot's An Intro to Git and GitHub for Beginners (Tutorial). 

_Reference_:
HubSpot Product Team. (2020, December 3). An Intro to Git and GitHub for Beginners (Tutorial). HubSpot Careers | Product, UX, & Engineering. Retrieved October 23, 2025, from https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners
