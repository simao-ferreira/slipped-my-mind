# git submodule

> Inspects, updates and manages submodules.
> More information: <https://git-scm.com/docs/git-submodule>.

- Clone a repository containing submodules:

`git clone --recurse-submodules {{repository_url}}`

- Install a repository's specified submodules:

`git submodule update --init --recursive`

- Add a Git repository as a submodule:

`git submodule add {{repository_url}}`

- Add a Git repository as a submodule with a different directory name:

`git submodule add {{repository_url}} {{path/to/directory}}`

- Add a Git repository as a submodule and set remote branch to track:

`git submodule add -b {{branch}} {{repository_url}}`

- Update every submodule to its latest commit:

`git submodule foreach git pull`

- Pull repository and submodules:

`git pull --recurse-submodules`

- Move submodule to a new directory

`git mv {{path/to/old}} {{path/to/new}}`
