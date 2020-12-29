Deployment Notes
-----
#### PR formatting:
Commit messages:  (https://chris.beams.io/posts/git-commit/)
* First word (imperatives) should be capitalised to be consistent with our other commits
```
  eg. 'Fix dashboard header'
      'Add new API endpoint'
```
* Git commit messages should only be separated by spaces, only use hyphens when needed
```
  eg. No - 'Fix-dashboard-header'
      Yes - 'Fix dashboard header'
```

* Put your initials on the branch use hyphen (-) for separating words
```
  eg. 'RG-Feature-Dashboard' (RG- Rufo Gabrillo)
      'MB-Remove-Old-API' (MB- Mark Barrios)
      
      
```
* Keep the commit message short (or not more than 50 characters)
* Further commit details can be put on the PR's description


## Git Cycle
1. Git pull from develop branch
```
git pull origin develop
```
2. Create a branch for the feature/fix
```
Feature/task-1010/html splash screen
Tweaks/task-1010/html splash screen
eg.
git checkout -b RG-Fix-Login-Issue
```
3. Commit changes
```
git add .
git commit -m'Bug fix'
```
4. push current branch
```
git push origin <BRANCH>

force push if needed:
git push -f origin <BRANCH>
```
5. comment PR request in proofhub card
