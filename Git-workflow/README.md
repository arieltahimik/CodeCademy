# Git workflow
The workflow for Git collaborations typically follows this order:  
  
1. **Fetch** and **merge** changes from the remote  
2. Create a branch to work on a new project feature  
3. Develop the feature on your branch and **commit** your work  
4. **Fetch** and **merge** from the remote again (in case new commits were made while you were working)  
5. **Push** your branch up to the remote for review  
  
Steps 1 and 4 are a safeguard against *merge conflicts*, which occur when two branches contain file changes that cannot be merged with the `git merge` command. Step 5 involves `git push`, a command you will learn in the next exercise.  

## Generalizations
Let’s review.

A remote is a Git repository that lives outside your Git project folder. Remotes can live on the web, on a shared network or even in a separate folder on your local computer.  

The Git Collaborative Workflow are steps that enable smooth project development when multiple collaborators are working on the same Git project.  

We also learned the following commands:  

`git clone` - Creates a local copy of a remote.  
`git remote -v` - Lists a Git project’s remotes.  
`git fetch` - Fetches work from the remote into the local copy.  
`git merge origin/master` - Merges origin/master into your local branch.  
`git push origin <branch_name>` - Pushes a local branch to the origin remote.  

<br>
