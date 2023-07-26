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


