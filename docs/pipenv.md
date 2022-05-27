# pipenv

> Simple and unified Python development workflow.
> Manages packages and the virtual environment for a project.
> More information: <https://pypi.org/project/pipenv>.

- Start a shell within the created virtual environment:

`pipenv shell`

- Install all the dependencies for a project:

`pipenv install`

- Install all the dependencies for a project (including dev packages):

`pipenv install --dev`

- Install a package:

`pipenv install {{package_name}}`

- Uninstall a package:

`pipenv uninstall {{package_name}}`

- Generate a `requirements.txt` (list of dependencies) for a project:

`pipenv lock --requirements`

- Alter a single package without updating unrelated packages:

`pipenv (install/uninstall/update) --keep-outdated {{package_name}}`

- Create a new project using Python 3:

`pipenv --three`

## Extra

Location of python SDK for created virtual environment on mac:

`/Users/{{user}}/.local/share/virtualenvs/{{pipenv-name}}/bin/python3`
