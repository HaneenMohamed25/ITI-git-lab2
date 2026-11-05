# Git task 2
### Tell me how to remove them locally and remotely?
● To delete a remote branch
git push origin :branch_name

● To delete a local branch
git branch -d branch_name

### Tell me how to checkout another branch without commit changes
git stash
then switch to the new branch then 
git stash pop -> to return changes when needed 

### Tell me how to list tags
git tag

### Tell me how to delete tag locally and remotely
 ● To delete remote tag
git push origin --delete v1.0

● To delete local tags
git tag -d v1.0

![lab2-image](happy.PNG)

# Task Done!