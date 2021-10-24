1.	git_1: Add and commit firstFile.txt file with 10 lines.
2.	git_1: Add and commit secondFile.txt file with 10 lines.
3.	Merge branch git_1 to git_2
 
4.	git_2: Update and commit any two lines in secondFile.txt.
5.	git_1: Update and commit the same 2 lines with the different info in secondFile.txt
 



6.	Merge branch git_2 to git_1, resolve conflict. Left all (4) modified lines. Commit.
 

7.	git_1: Update and commit 1.txt file, modify two lines.
8.	git_1: Update and commit 1.txt file, modify another two lines
 


9.Transfer changes of commit from Step 7 only to git_2, using format patch
 
10.	Transfer changes of commit from Step 8 only to git_2, using cherrypick command.
 
11.	git_2: Concatenate the last two commits using reset + commit commands.
 

12.	git_2: Change date, author and message of the last commit and add non-empty thirdFile.txt file to it.
 
 
13.	git_2: Create a new commit that reverts changes of the last one.
 
14.	git_2: Create and commit thirdFile.txt file.
15.	git_2: Run command that removes all changes of the last two commits.
 
16.	Synchronize git_1 and git_2 with a remote repository.

 






17.	Clone your project to another folder.

 
18.	folder2: git_1: Change two lines in firstFile.txt. Commit + Push.

 
19.	folder1: git_1: Change another two lines in firstFile.txt.
20.	*folder1: git_1:
a.	Chaaznge another line in firstFile.txt (not the same as in 18, 19).
b.	Merge changes from Step 18 (pull) without committing changes from Step 19 and any additional commits.

 
•	Push.
•	Return local state of Step 19. (stash)
 


 

 
