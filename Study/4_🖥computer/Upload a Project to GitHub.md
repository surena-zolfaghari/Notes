[[4_🖥computer/Git]]
#git #GitHub
# Upload a Project to GitHub
This work is very simple and pass step by step. First of all you should initialize a repository. After creating a repository on GitHub (Note: Don't initialized with README.ma or .gitignore or Licence just create this)

```git
echo "# today" >> README.md
git init 
git add .
git commit -m "Your massage"
git branch -M main
git remote add origin < HTTPS of Repository >
git push origin main
```


If you want to work on experimental project, It's better to work on a new branch. Follow this instructions:

There are two command for creating a branch. The first command creates a new branch but remain at the current branch. The second command creates a new branch and will switch to new branch.
```git
git branch < name of branch that you want >
```
OR
```git
git checkout -b < name of branch that you want >
```


Now I want to work on test branch for this purpose should all of the file copy and move on to test branch 
```git
git add . 
git commit -m "Your massage"
git push origin < name of branch >
```


If you want to merge a branch to default branch. First of all you should to check out to default branch. And then you can use the below command:
```git
git merge < Name of your branch >
```


After merging two branches, you can delete the second branch. Because all of changes pushed to default branch. For this goal see below:
```git
git push origin :mybranch         (Deleting a remote branch)
git branch -d mybranch            (Delete a branch)
```

```git

```

