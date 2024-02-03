# React + Vite app

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.


## Git SETUP!

### Git global setup
```
git config --global user.name "Mohamed Khasim"
git config --global user.email "Khasimrockers@gmail.com"
```

### Clone a Repo
```
git clone git@github.com:k3XD16/myreact-app.git
```
a
### Create a new Repo
```
git remote add origin git@github.com:k3XD16/myreact-app.git
cd /to/your/working/directory/
git switch --create main
touch README.md
git add README.md
git commit -m "add README"
git push --set-upstream origin main
```

### Push an existing folder
```
cd existing_folder
git init --initial-branch=main
git remote add origin git@github.com:k3XD16/myreact-app.git
git add .
git commit -m "Initial commit"
git push --set-upstream origin main
```

###  Push an existing Git repository
```
cd existing_repo
git remote rename origin old-origin
git remote add origin git@github.com:k3XD16/myreact-app.git
git push --set-upstream origin --all
git push --set-upstream origin --tags
```

### for warning: LF will be replaced by CRLF
```
git config --global core.autocrlf true
```

<!-- ## Three Branches
### main, k3xd16 and mkhasi -->

### fetch and check out this merge request's feature branch:

```
git fetch origin
git pull
git checkout -b 'k3xd16' 'origin/k3xd16'
git checkout -b 'mkhasi' 'origin/mkhasi'
```
### Tip: You can also check out with merge request ID.

### Push the source branch up to GitLab.

```
git push origin 'main'

```