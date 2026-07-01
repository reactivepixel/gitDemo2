# Git Notes

## All Commands

anything in <>'s are your choice

```bash
git init								// intialize the git repo
git status								// im lost, hlp plz

git add <filename>						// add a single file to the stage
git add -A								// stage all files not in the ignore
git commit -m "<msg>"					// exe the commit of what is on the stage

git log									// list of commits

git remote add origin <url>				// connection to github, has to be setup on github.com

git checkout -b <branchName>			// creates a new branch
git checkout <branchName>				// change to branch


git tag -a '<verNumber>' -m '<msg>'		// tags the current commit

git push origin <branchName>			// exopse target branch on github... or push or sycn
git push origin --tags					// tags must be push sepreatly

git pull origin <branchName>			// sync down remote to local changes
git reset --hard <id>					// go back in time to target commit
git diff								// show diff between commits
```

## Common Commands

```bash
git add -A
git commit -m "<msg>"
git checkout <branchName>

git pull origin <branchName>
git push origin <branchName>
```


> Oddball Cmds

```
clear
history
```