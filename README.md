```
                                                  GIT ASSIGNMENT 
```
<img width="771" alt="Screenshot 2023-01-25 at 12 14 39 PM" src="https://user-images.githubusercontent.com/122472996/214503335-85cfc574-e8e7-4662-885f-854f7b87f8c8.png">

1.First Step,
 - I created the Repository in Github and cloned in local enviroment.
 - And then created HotFix and Integration Branch which is braching out of Main Branch.
 
2.Second Step,
 - Creating Two Branches Feature1 and Feature2 out of Integration Branch.
 - Adding some changes then adding 2 reviewers by help of him merging the pull request to integration.

 
3.Third Step,
  - In Local Enviroment , changing and commit in Feature1.
  - But Now, we want ahead of the merge happend in the origin/Feature2. So we do this command to rebase `git pull --rebase`. It means our local commit will     ahead of previous commit while pulling from the remote.
  
4.Fourth Step,
   -  Changes in Integration branch merged into Production(main) and HotFix branch
 
5.Fifth Step,
   -  In HotFix branch made a quick fix and merged into Integration and Production branch
6.Sixth Step,
   -  Finally deleted Feature1, Feature2, HotFix branches after completing the above steps.
 
$${\color{blue}**Commands Used**}$$	

1. `git clone`
2. `git log --online`
3. `git push`
4. `git pull`
5. `git checkout`
6. `git branch`
7. `git checkout -d [branch name]`
8. `git checkout -b [branch name]`

                                  
  
