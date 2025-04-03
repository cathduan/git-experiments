# git-experiments
test GitHub for cs347

# Part 1

## Charlie
Step 1: git clone https://github.com/cathduan/git-experiments.git

Step 2: touch charlie.txt

Step 4: git add charlie.txt

Step 5: git commit -m "added charlie.txt file"

Step 6: git push

### Cathy

Step 1: git clone https://github.com/cathduan/git-experiments.git

Step 2: touch cathy.txt

Step 3: git add cathy.txt

Step 4: git commit -m "Add cathy.txt"

Step 5: git pull

Step 6: git config pull.rebase false
Note: Our branches had diverged so I had to run this as recommended by git.   

Step 7: git commit -m "merge"

Step 8: git push 
Note: I had to set up a PAT, but then it worked. 

## Part 2

Step 1: git checkout Charlie (to create new branch)

Step 2: edited charlie.txt

Step 3: Added and commited changes

Step 4: git push origin Charlie

Step 5: Created the pull request

Step 6: Reviewed and accepted pull request

Step 7. git pull

Step 8. git log (we saw changes on the Charlie branch and the merged pull request)

## Part 3

Step 1: We both edited the same line of thhe cathy.txt file

Step 2: one of us commited and pushed, the other tried to pull

Step 3: ran into a merge conflict

Step 4: chose the changes to keep

Step 5: commited the merged changes

Step 6: pushed merge