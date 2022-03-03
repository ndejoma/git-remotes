# Steps  to Creating a new Branch Locally and pushing it to remote
  1. Create a new branch and check it out **git checkout -b <new_branch>**
  2. Create a new file BranchCreation.md, edit it and commit it.
      ```git
      git touch BranchCreation.dd
      git add BranchCreation.dd
      git commit -m "Describe how to create branches"
      ```
  3. Push the branch to Remote using:
     ```git
       git push -u origin <new_branch>
    
