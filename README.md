# Learning MD by creating a git notes document
## Common git commands
##### creating a project
```
git init
git add .
```
##### commiting
```
git commit -a -m "commit message"
```
##### adding repo to commit to
```
git remote add origin "your_origin_link_here"
```
##### look to where you're pushing/fetching to/from
```
git remote -v
```
##### create a new branch
```
git checkout "your_new_branch_name_here"
```
##### check branch diffs
```
git diff "your_branch_to_check_here"
```
##### push to repo
```
git push origin master
```
## Git File States:
- untracked:
not being tracked
- staged:
marked for next commit
- committed:
saved to history
