# Git Remotes
Working with Git remotes

## The default Remote for Git is origin

### Committing changes to Remote
   1. Clone this Repo
   2. Edit the README.md files.
   3. Add the README.md file to the the staging area(index) git add <file_name>
   4. Add it to the commit using git commit -m "Commit message"
   5. To commit it to Remote,use  git push. Which pushes only the Objects not available in the remote, that is the (Trees, Commits and Blobs), tags may be included using git push --tags. The --tags options instructs git to send all tags under == refs/tags ==, including Annotated tags which are Objects in Git.

   6. When you use ==git push== without specifying anything. Git will send all new commits and their associated objects you did locally in the currently checked out branch. 

   7. **git push --tags** pushes all the tags included in the **.git/refs/tags** folder