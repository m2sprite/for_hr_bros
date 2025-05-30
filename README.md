![img place](/imgs/repo_header_img.png)
## Common git commands
- **turning a dir into a repo**
```
git init
```
- **add files to track**
```
git add .
```
- **inspecting repo**
```
git status
```
- **commiting**
```
git commit -m "your_commit_message"
```
- **adding origin location to push to**
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
git checkout -b "your_new_branch_name_here"
```
- **check branch diffs**
```
git diff "your_branch_to_check_here"
```
- **push to repo**
```
git push origin "your_branch_name"
```
- **view commit history starting from most recent**
```
git log --oneline
git log --oneline --graph //graphing enabled
git log --oneline -n10 --graph //last 10 commits graph
```

## Git File States:
- `untracked`: not being tracked
- `staged`: marked for next commit
- `committed`: saved to history
