# Git Commands Cheat Sheet

## `git remote`
* Check current git remote status:
	- `git remote -v`
* Rename `{REPO_NICKNAME}`
	- `git remote rename {OLD_REPO_NICKNAME} {NEW_REPO_URL}`
* Remove a `{REPO_URL}`
	- `git remote rm {REPO_NICKNAME}`
* Add new git repository address: 
	- `git remote add {REPO_NICKNAME} {REPO_URL}`
	- e.g.: `git remote add origin git@github.com:mt1ger/woLPS_SEG_SimSDM-EON.git`
* Change an existing remote repository URL: 
	- `git remote set-url {REPO_NICKNAME} {NEW_REPO_URL}`
	- e.g.: `git remote set-url origin git@github.com:mt1ger/woLPS_SEG_SimSDM.git`

## `git push`
* Push a branch
	- `git push {REPO_NICKNAME} {BRANCH_NAME}`
* Push the whole local workplace
  -	`git push --mirror {REPO_NICKNAME}`

## `git pull`

## `git commit`
* Normal commit with message
	- `git commit -m "{COMMIT_MESSAGE}"`

## `git checkout`
