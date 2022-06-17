Hello
Привет, GitHub и мир

## Git branch
- List all of the branches in your repository. This is synonymous with git branch -- list.

## Git branch  *< branch >*
- Create a new branch called **＜branch＞**. This does not check out the new branch.

## Git checkout *＜branchname＞*
- Switching branches is a straightforward operation. Executing the following will point HEAD to the tip of **＜branchname＞**.

## Git checkout *-b ＜ new-branch ＞*
- This command simultaneously creates and checks out **＜new-branch＞**. The ***-b*** option is a convenience flag that tells Git to run git branch  before running git checkout **＜new-branch＞**

## Git branch *-d < branch >*
   - Delete the specified branch. This is a *“safe”* operation in that Git prevents you from deleting the branch if it has unmerged changes.

## Git branch *-D < branch >*
 - Force delete the specified branch, even if it has unmerged changes. This is the command to use if you want to permanently throw away all of the commits associated with a particular line of development.

## Git merge *< branch >*
- This command merges the specified branch into the current branch

## Git branch *-m < branch >*
- Rename the current branch to a **＜branch＞**

## Git clone *git clone < repo >*
- Clone the repository located at ＜repo＞

## Git push 
The git push command is used to upload local repository content to a remote repository.

## Git pull
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

