# git squash

> Reorder or squash commits from one branch.
> More information: <https://git-scm.com/docs/git-rebase>.

- Start an interactive rebase, which allows the commits to be reordered, omitted, squashed or modified:

```
git log --oneline {{source_branch}}

# selected commit reference (something like 0faf1a8) will not be included

git rebase -i {{commit_reference}}
```
