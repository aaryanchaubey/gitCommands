# Collaboration

A Github Repository acting as a Git Cheat Sheet for all the enthusiats Github Developers

---

## Normal Git Commands

Clones the repository in your machine
```
git clone <'git repo'>
```

Create a new file 
```
touch <fileName.type>
```

Open File in VS Code
```
code <fileName>
```

Add all the files in staging area
```
git add .
```

Commit all the changes from the staging area
```
git commit -m "message"
```

Push

- Push The changes in the repository from main branch
```
git push 
```

- Push Changes in repository from different branch other than main
```
git push origin <branchName>
```
---

If anything has been added in the staging area and You dont want to commit it and also not delete it, then you can save it in the stack 

Makes the staged changes unstage and saves in the stack therby making working tree clean
 ```
 git stash
 ```
 
Brings back the changes from the stack
```
git stash pop
```

---

## Branching

To create a new branch
```
git branch <branchName>
```

To switch to a particular branch
```
git checkout <branchName>
 ```

To check the current and exisiting branches
```
git branch
``` 

## Delete the Branch
- Locally delete
```
git branch -d <branchName>
```
  
- Github delete
```
git push origin --delete <branchName>
```

---
 
## Merging
1. Checkout to the branch where you want to merge
```
git checkout <branchName> 
```

2. The branch you want to merge
```
git merge <branchName>
```

---
  
## Fork and Pull from Github 

- Fork a repo :  Creates a copy of the repo in your Github
- Change the required changes
- Send a pull request
