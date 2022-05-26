# sport
[![Python application](https://github.com/RGGH/sport/actions/workflows/python-app.yml/badge.svg)](https://github.com/RGGH/sport/actions/workflows/python-app.yml)
## Example project structure created with "Poetry" 
---
### 
    -Automate GitHub actions
    -Create standard project structure
    -Run pytest on every push
---

    $ poetry new --src sport
    # change to lower dir that contains pyproject.toml then start virtual env
    $ poetry shell
    $ poetry env list
    $ poetry add requests
    $ poetry export --output requirements.txt


![sport](https://github.com/RGGH/Misc/blob/master/s4.png)

https://realpython.com/pypi-publish-python-package/#poetry

https://python-poetry.org/

### Bash script to automate : 

    #!/bin/bash   
    echo "Give a directory name to create:"    
    read NEW_DIR    
    ORIG_DIR=$(pwd)    
    [[ -d $NEW_DIR ]] && echo $NEW_DIR already exists, aborting && exit    
    mkdir  $NEW_DIR    
    echo "new directory made ${pwd}"
    cd $NEW_DIR
    poetry new app
    cd app 
    poetry shell
    code .


