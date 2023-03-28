# How to use Poetry for package management in Python

## Steps

- Install poetry: ```pip install poetry```
- For a new project, you need add a pyproject.toml file: ```poetry init```
- Create a venv and install packages: ```poetry install```
- Get info on where this venv is located: ```poetry env info```
- Remove the venv if it is in some local cache folder: delete the old venv
- Instead, install the venv inside the project folder: ```poetry config virtualenvs.in-project true```
- Then do: poetry install (folder should get created inside project now)
- Run a program inside the venv: ```poetry shell```
- Run code: e.g ```pytest```
- Add dependancy: ```poetry add requests```
- Remove dependancy: ```poetry remove requests```
- Get out of venv shell: ```exit```
- List active environments: ```poetry env list```
- Go back into shell: ```poetry shell```
- Deactivate venv: ```deactivate```
- Remove venv: right click delete folder venv

## Important
1. Manage dependancies properly. Keep updating your project files. (Else module not found errors).
2. Activate venv before running code. (Create venv inside project folder)
3. Some compatibility issues??
4. Virtual environments can get large! If lots of projects, and lots of venv, then you need more disk space. Or delete venv that you don’t use.

## Source
https://youtu.be/0f3moPe_bhk
