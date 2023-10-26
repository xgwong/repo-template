# repo-template
template for setting up new repos

## Dependencies Installation
* Preferable to use virtual environment(e.g: venv), to prevent mess up dependency with other python project if any.
```
pip install -r Dependencies/requirements.txt
```

pre-commit hook
```
# ensure pre-commit is here after you install requirements-dev.txt
pre-commit --version

# install pre-commit as part of git hook scripts
pre-commit install

# update hooks to latest version
pre-commit autoupdate

# now pre-commit will run automatically on 'git commit'
# the configuration is on .pre-commit-config.yaml

Reference : https://pre-commit.com/index.html#install
```
