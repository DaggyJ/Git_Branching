# Git_Branching
Learning git branching

## Define terms
.Branch;
        is a pointer to a spectific commit which allows developers to work on diffirent aspects on the same project on the same time without affecting the code base
        is an indipendent line of development
    Benefits of branches
1. isolation: allows developers to work of features without interfering the main project
2. Parallel development: Multiple developers can work in a collaborative coding

commit message

## Git Commands
1. Create a branch
```bash
    git branch "branchname"
```
2. Switching between Branches; helps in the deelopment context
```bash
    - git switch "branchname"
        or
    - git checkout "branchname"
```
    Directly switching to a new branch
```bash
    git checkout -b 
                    "-b; is used to create a branch" & 
                    "checkout is used to switch to that branch"
```

3. Merging; is necessary when completing a feature or resolving a back from the context that we gave
```bash
    git merging "sourcebranch"
```
4. Resolve Conflict/Errors
```bash
    git mergetool
```

git branch
git status
git branch -b
git branch -merged
    list merged commits
git branch --merged
    list unmerged commits

