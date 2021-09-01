# {{cookiecutter.project_name}}

## Setup
```sh
# Install pipenv 
pip install pipenv

# create virtual environment, Install dependencies
pipenv install --dev

# Setup pre-commit
pipenv run pre-commit install
```

IDE need to know where the virtual env create by pipenv is located
Here are some links that explain how to set up pipenv interpreter
- [VS Code](https://developpaper.com/configuring-pipenv-virtual-environment-with-python-of-vscode/)
- [PyCharm](https://www.jetbrains.com/help/pycharm/pipenv.html)
