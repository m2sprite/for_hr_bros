# Learning MD by creating a git notes document
## Common git commands
- **turning a dir into a repo**
```
git init
git add .
```
- **inspecting repo**
```
git status
git commit -a -m "your_commit_message"
```
- **commiting**
```
git commit -a -m "your_commit_message"
```
- **adding repo to commit to**
```
git remote add origin "your_origin_link_here"
```
- **look to where you're pushing/fetching to/from**
```
git remote -v
```
- **inspecting branch**
```
git branch
```
- **create a new branch**
```
git checkout "your_new_branch_name_here"
```
- **check branch diffs**
```
git diff "your_branch_to_check_here"
```
- **push to repo**
```
git push origin master
```
- **view commit history starting from most recent**
```
git log --oneline
git log --oneline --graph //graphing enabled
```

## Git File States:
- `untracked`: not being tracked
- `staged`: marked for next commit
- `committed`: saved to history
