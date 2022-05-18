# sport

## Example project structure created with "Poetry" 
---
### 

[![Python application](https://github.com/RGGH/sport/actions/workflows/python-app.yml/badge.svg)](https://github.com/RGGH/sport/actions/workflows/python-app.yml)

## $ poetry new --src heli
$ cd helicopter

── heli1
   ├── heli1
   │   └── __init__.py
   ├── pyproject.toml
   ├── README.rst
   └── tests
       ├── __init__.py
       └── test_heli1.py


----------- change to lower dir that contains pyproject.toml
$ cd heli1
$ cd heli1
# !! then start virtual env
$ poetry shell
---------------

// The easiest way to activate the virtual environment is to create a new shell with:
$ poetry shell. 

// To deactivate the virtual environment and exit this new shell type 
$ exit

// check for virtual environment
$ poetry env list

// Show virtual env info
$ poetry env info

// import requests
$ poetry add requests

// create requirements.txt
poetry export --output requirements.txt


------ Links -------

https://realpython.com/pypi-publish-python-package/#poetry

https://python-poetry.org/

--------------------
