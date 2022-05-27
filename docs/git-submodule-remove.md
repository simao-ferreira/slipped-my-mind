# git submodule

> Inspects, updates and manages submodules.
> More information: <https://git-scm.com/docs/git-submodule>.

- Remove git submodule:

```
git submodule deinit {{submodule}}
rm -rf .git/modules/{{submodule}}
git rm {{submodule}}
```

- Alternative to remove git submodule:

```
git rm {{submodule}}
rm -rf .git/modules/{{submodule}}
git config --remove-section submodule.{{submodule}}
```

- In case removing the configuration does not work, just remove manually the lines regarding the submodule from `.git/modules/config`
