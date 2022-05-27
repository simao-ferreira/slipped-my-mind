# python pip

> Python package manager.
> More information: <https://pip.pypa.io>.
> Should be used from a virtual environment.

- Install dependencies from a file, usually requirements.txt:

`pip install -r {{path/to/requirements.txt}}`

- Update all packages in requirements.txt:

`pip install -U -r requirements.txt`

- Install a package:

`pip install {{package_name}}`

- Install a specific version of a package:

`pip install {{package_name}}=={{package_version}}`

- Update one package:

`pip install -U {{package_name}}`

- Uninstall one package:

`pip uninstall {{package_name}}`

- Save the list of installed packages and versions, if file exist it will need to be deleted:

`pip freeze > requirements.txt`

- Show installed package information:

`pip show {{package_name}}`

- Check missing dependencies:

`python -m pip check`

- List all outdated packages:

`pip list --outdated`
