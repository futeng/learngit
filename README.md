### Config
1. git config --user.name "Your Name"
2. git config --user.email "Your Email"
3. git init
4. git branch

### Working together

1. Get romote info

```
git remote -v
```

2. Create local branch which recommened use the same name as remote branch

```
git checkout -b branch-local-name origin/branch-name
``` 

3. Connect local branch to remote branch

```
git branch --set-upstream branch-local-name origin/branch-name
```

4. Pull remote branch 

```
git pull
```

5. Push local modified to remote

```
git add FILE
git commit -m "modified FILE for some reason"
