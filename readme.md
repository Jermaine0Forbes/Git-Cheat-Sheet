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
```
- summary

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

