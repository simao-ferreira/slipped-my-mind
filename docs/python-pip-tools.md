# python pip-tools

> Manage Python packages.
> More information: <https://github.com/jazzband/pip-tools>.
> Should be used from a virtual environment

- Install pip-tools:

`pip install pip-tools`

- Generate requirements file, usually requirements.in:

`pip-compile {{path/to/requirements.in}}`

- Update requirements file:

`pip-compile --upgrade`

- Update single package:

`pip-compile --upgrade-package {{package_name}}`

- Update single package to a specific version:

`pip-compile --upgrade-package {{package_name}}=={{package_version}}`
