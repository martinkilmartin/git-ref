# git-ref
Reference for f̶r̶e̶q̶u̶e̶n̶t̶l̶y̶ ̶o̶r̶ ̶i̶n̶f̶r̶e̶q̶u̶e̶n̶t̶l̶y̶ ̶u̶s̶e̶d̶  git commands

## Fork own repo on GitHub

1. Create new repo
2. Clone new repo
3. Add remote upstream ```git remote add upstream https://github.com/<username>/<original-repo>.git```
4. Update from remote ```git pull upstream main```
5. Push to origin ```git push origin main```

## Create branch (with current changes)

```git checkout -b <branch-name>```

## Modify most recent commit
### *Combines staged changes with previous commit instead of creating new commit*
### *Can be used to edit previous commit message without changing its snapshot*

```git commit --amend -m "Replaces previous commit message"```
