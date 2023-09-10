# practice_github with Bharti
Now there are two methods to create file one is from github and another one is directly from pc local
if i am creating file in githb first and then cloning it into my local system then while making changes in this file i have to use command git add . (to add all files), then git commit to commit files, then my files will get tracked in git system, then push these files to update in remote repository with the command git push origin main
now if i make files in local first then i have to use git init, then other commands which comes on the repository while creating it.

C:\Users\hp\Desktop\practice_github>git checkout -b main2-> create another branch
know at which branch we are working--> git branch
swithc branch--> git checkout main
now whatever things are there they are only in main branch there is nothing in main2 branch
git log--> show history of all commits
git log branchB..branchA, show the commits on branchA that are not on branchB
C:\Users\hp\Desktop\practice_github>git log -- branchmain2..branchmain
C:\Users\hp\Desktop\practice_github>git restore --staged README.md restore the commit 

