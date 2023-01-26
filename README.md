# Git_Assignment
This is my Git assignment

Feature_1
Step 4: Commiting this change to Feature_1 branch.
Feature_2
Third step: Commiting this change to the Feature_2 branch.

Step 6: Commiting this change to Feature_1 branch.

Step 7: Commiting this change to HotFix branch.

# Step 8: Proper README for the "Git_Assignment" repository

- Created a directory __Git_Assignment__ at the desktop and initialized a git repository inside this directory using "git init ." command.
- Now we were on the master branch. Then created two branches __Integration__ and __HotFix__ using "git checkout -b \<branch-name>" command.
- Created two sub-branches, __Feature_1__ and __Feature_2__, from the __Integration__ branch.
- Then created new remote repository on github.com with a __README.md__ file.
- Set both, the __master__ branch of local repository and __origin/master__ branch of the remote repository to track each other, where __origin__ is the     reference for the remote repository.
- Pushed __Integration__, __HotFix__, __Feature_1__ and __Feature_2__ branches on the remote repository and set them up with __origin/Integration__,         __origin/HotFix__, __origin/Feature_1__ and __origin/Feature_2__ branches to track each corresponding branch.
- Pulled all the changes from remote repository to the local repository, to bring down the __README.md__ file.
- Switched to the __Feature_2__ branch on the local side and made some changes to the __README.md__ file.
- Pushed the changes made in local __Feature_2__ branch to the __origin/Feature_2__ branch.
- Created pull request for the changes in __origin/Feature_2__ branch to be reviewed by two reviewers Mahesh and Karan, and be merged into                     __origin/Integration__ branch. 
- Deleted the __Feature_2__ branch locally and pushed this deletion to the remote repository for removing its stale reference __origin/Feature_2__ using     "git push origin :/<branch_name>".
- Switched to the __Feature_2__ branch locally and made some changes in the __README.md__ file and rebased it to the local __Integration__ branch, resloved   merge conflicts using __p4merge__ mergetool, commited those changes to the __REDAME.md__ file which was one of the two given options from "git add/rm       /<conflicted_files>" and used the command "git rebase --continue" to move forward with rebase successfully.
- Created two different pull requests remotely for __origin/Integration__ to be reviewed by two reviewers and be merged into the __origin/HotFix__ and the   __origin/master__ branches.
- Switched to the __Feature_1__ branch on the local side and made some changes to the __README.md__ file.
- Pushed the changes made in local __Feature_1__ branch to the __origin/Feature_1__ branch.
- Created three different pull requests for the changes in __origin/Feature_1__ branch to be reviewed by two reviewers Mahesh and Karan, and be merged into   __origin/Integration__, __origin/HotFix__, __origin/master__ branches . 
- Deleted the __Feature_1__ branch locally and pushed this deletion to the remote repository for removing its stale reference __origin/Feature_1__ using     "git push origin :/<branch_name>".
- Switched to the __HotFix__ branch on the local side and made some changes to the __README.md__ file.
- Pushed the changes made in local __HotFix__ branch to the __origin/HotFix__ branch.
- Created two different pull requests for the changes in __origin/HotFix__ branch to be reviewed by two reviewers Mahesh and Karan, and be merged into       __origin/master__ and __origin/Integration__ branches.

__NOTE__: __master__ branch on the local side and __origin/master__ branch on the remote side refers to the __Production__ and __origin/Production__                 branches on the local and remote repository respectively.

__Screenshot__ for the "git hist" command:

<img width="1440" alt="Screenshot 2023-01-26 at 10 26 49 AM" src="https://user-images.githubusercontent.com/122514456/214762164-41bf2dce-68ba-45ce-a9ef-63125342968b.png">
