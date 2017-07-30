# git commands

[home]:#git-commands


### git revert

```
	git revert < insert commit number>
```
- It reverts an old commit an allows you to change the message of the commit

[go back to home][home]


### git reset

```
	git reset --soft <insert commit id number >
```
- allows you to go back to a older commit and make it the most recent one. In addition, you can also undo the the changes by using  the soft reset with original recent commit id


```
	git reset --mixed <insert commit id number>
```
- Is very similar to  reset soft, except if you want to undo changes you have to use the **git reset HEAD "insert file name"** and then do git reset --mixed. To finally revert back to the original commit you had in your log


```
	git reset --hard <insert commit id number>
```
- changes staging index and working directory to match repository/folder


[go back to home][home]


### git rm

```
	git rm <insert path name>
```
- to remove files

[go back to home][home]

### git mv

```
	git mv <old file path> <new file path>
```
- this changes the file path to a new location

```
	git mv oldFile.txt newFile.txt
```
- git mv also changes the file name

[go back to home][home]


### git checkout

```
	git checkout -b <insert branch name>
```
- creates a new branch and switches to it

```
	git checkout <insert branch name>
```
- switches to a different branch

```
	git checkout <insert file name>
```
- undo working directory changes

```
	git checkout <insert commit id number> --<insert file name>
```
- retrieve old version of a file that has been committed

[go back to home][home]

### git stash

```
	git stash save "insert message"
```
- saves a modified state from a branch that you don't want to add in the staging index

```
	git stash list
```
- shows a list of things that were saved in the stash

```
	git stash show <insert stash expression>
```
- shows what has been changed

```
	git stash show -p <insert stash expression>
```
- shows more in depth was has been changed

```
	git stash pop <insert stash expression>
```
- adds files that were in the stash to the current branch and removes the stash it as well

```
	git stash apply <insert stash expression>
```
- adds files that were in the stash to the current branch

```
	git stash drop <insert stash expression>
```
- removes the selected stash

```
	git stash clear
``` 
- clears out all the saved stashes


[go back to home][home]


### git remote

```
	git remote
```
- shows all the remotes that we are working with

```
	git remote -v
```
- gives more information about the remotes in the repository


[go back to home][home]

### git

```
```
- summary

[go back to home][home]


### git

```
```
- summary

[go back to home][home]

