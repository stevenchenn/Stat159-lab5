User A: Steven Chen
User B: Thomas Sun

Task 1
------
We created different files at different times, therefore there was no conflicts in our changes. When User A modified file1.txt, User B never changed the same file, so there was no conflicts.

Task 2
------
We modified the same file at the same time, which led to a pull conflict. User A pushed first, so when User B tried to pull the changes, conflict arised for file2.txt. User B had to pick which version to keep or modify file2.txt to incorporate the changes and push the changes to master.

Task 3
------
When User B modified file1.txt in the new branch, he isolated the changes to that specific branch. However, he merged the changes to master and pushed. Since User A already modified file1.txt in master branch, there was no isolation. Therefore, conflict emerged when User A tried to pull the changes.

Task 4
------
User A and User B branched separately off from master and editted different files. Therefore when both users merged back to master and pushed, no conflicts emerged.

Task 5
------
ALthough both users worked on different branches, the editted the same files. Therefore, when User B merged his changes to master and pushed to remote, User A saw conflicts when he tried to pull the changes. This is because they worked on the same file. So User A had to fix the merge conflict by changing file1.txt to incorporate both changes, or delete one of the changes before pushing to the remote.

