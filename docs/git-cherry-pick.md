# git cherry-pick

> Apply the changes introduced by existing commits to the current branch.
> To apply changes to another branch, first use `git checkout` to switch to the desired branch.
> More information: <https://git-scm.com/docs/git-cherry-pick>.

- Select a commit from another branch, pick the commit reference and apply
  it to the current branch:

```
git log --oneline {{source_branch}}

# copy the commit reference (something like 0faf1a8)

git cherry-pick {{commit_reference}}
```

- Apply a range of commits to the current branch (see also `git rebase --onto`):

`git cherry-pick {{start_commit_reference}}~..{{end_commit_reference}}`

- Apply multiple (non-sequential) commits to the current branch:

`git cherry-pick {{commit_1_reference}} {{commit_2_reference}}`

- Add the changes of a commit to the working directory, without creating a commit:

`git cherry-pick -n {{commit_reference}}`
