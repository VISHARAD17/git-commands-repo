## Imp git commnds that I use regularly

- Initializing a git repo
``` 
git init
```
- rename the default branch of local and remote repo to same name `main'
```
git branch -M main
```
- Add remote origin to push the code to the remote repo which is on github
```
git remote add origin link_to_the_repo
```
- push code to the remote branch from local `main` branch
```
git push -u origin main
or
git push origin main
```
- Remove all the files from the git staging area
``` 
git rm --cached -r .
```
- Create a new branch and switch to it immediatly
```
git branch -b branch_name
```