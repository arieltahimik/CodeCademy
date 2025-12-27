# tasks.md
1. Enter this command:
```bash
cd my-quizzes
```

<br>
  
2. Enter the Git command:
```bash
git branch bio-questions
```
to create a branch to develop questions for the biology quiz. Name the branch bio-questions.  
  
Note: be careful to spell the name “bio-questions” exactly as it appears.  

<br>

3. Switch to your new branch with the command:  
```bash
git checkout <branch_name>
```
replacing `<branch_name>` with the name of the new branch.  

<br>

4. On your branch, open the file `biology.txt` under the `my-quizzes` folder in the code editor (make sure you are editing the correct biology.txt file).

Add a biology question to the file and some sample answers. For example:  

What is an animal that hunts and eats other animals called?  
a) herbivore  
b) prey  
c) ecosystem  
d) predator  

<br>

5. Add biology.txt to the staging area.  
```bash
git add biology.txt
```

<br>

6. Commit the work to the repository with a commit message.  
```bash
git commit -m "Add question to biology.txt"
```

<br>

The command:   
```bash
git push origin <your_branch_name>
```
will `push` your branch up to the `remote, origin`. From there, a co-developer can review your branch and `merge` your work into the `master` branch, making it part of the definitive project version.

7. Enter this command:
```bash
cd my-quizzes
```
to change directories into the `my-quizzes` directory.

<br>

8. Push your branch up to the remote.
```bash
git push origin bio-questions
```

In the output, notice the line:
```bash
To /home/ccuser/workspace/curriculum-a/science-quizzes
 * [new branch]      bio-questions -> bio-questions
```

Git informs us that the branch `bio-questions` was pushed up to the remote. Another can now review your new work and can `merge` it into the remote’s `master` branch.  

<br>