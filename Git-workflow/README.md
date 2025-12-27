# Git workflow
The workflow for Git collaborations typically follows this order:  
  
1. **Fetch** and **merge** changes from the remote  
2. Create a branch to work on a new project feature  
3. Develop the feature on your branch and **commit** your work  
4. **Fetch** and **merge** from the remote again (in case new commits were made while you were working)  
5. **Push** your branch up to the remote for review  
  
Steps 1 and 4 are a safeguard against *merge conflicts*, which occur when two branches contain file changes that cannot be merged with the `git merge` command. Step 5 involves `git push`, a command you will learn in the next exercise.  
