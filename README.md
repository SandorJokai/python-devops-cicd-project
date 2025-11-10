# python for DevOps: CI/CD Python Project
This repo contains the code for the CI/CD section of my Python for Devops course.

## What we implement in this repository

- [x] Implement the project (code files)
- [x] Add a simple GHA workflow and make sure it runs until completion
- [x] Add linting (ruff) and format (black) checks
- [x] Add typing (mypy) and security (bandit) checks
- [] Add typing and security checks
- [] Add test automation
- [] Build our Python project
- [] Publish the project to both TestPypi and PyPi when a new tag is pushed

## Documentation for ruff linting module
https://docs.astral.sh/ruff/configuration/

## Documentation for mypy & bandit typing and security checkers
https://mypy.readthedocs.io/en/stable/config_file.html#using-a-pyproject-toml-file
https://bandit.readthedocs.io/en/latest/config.html

## Setup a virtual envitonment for python in my case
```bash
python3.9 -m venv --without-pip .venv
source .venv/bin/activate
```
