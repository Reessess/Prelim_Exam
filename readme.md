# This is my setup github
## Step
### Setup
1. Create a project
2. Convert that project into a local repository or initialize is as local repo
```bash
git init
```
- Setup your user.name and email.address
```bash
git config --global user.name "Reessess" 
git config --global user.email "Jrees025@gmail.com"
```
3. Create a remote repo on github
4. Connect local and remote so they'll in sync
```bash
git remote add origin https://github.com/Reessess/Prelim_Exam.git
```
5. Push or upload local changes to remote repo
```bash
 git add .
 git status
 git commit -m "Warm up"
 git push -u origin main
 ```