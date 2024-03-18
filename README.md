# FAP - Flipper Application Package

## Build Flipper Application Package (.fap)

Create GitHub Repositorie -> [Link](https://github.com)

Clone Repositorie in VSCode

Create Virtual Environment
```
python -m venv venv
```

Enter Virtual Environment
```
venv/scripts/activate
'''

[Link](https://github.com/marketplace/actions/build-flipper-application-package-fap)

'''
python -m pip install --upgrade pip
python -m pip install --upgrade ufbt
pyenv rehash
'''

Create And Run Inside Folder
'''
ufbt create APPID=<app_name>
ufbt
ufbt launch
'''



List All Requirements
```
pip freeze
```

Add All Requirements
```
pip freeze > requirements.txt
```

Install All Requirements
```
python3 -m pip install -r requirements.txt
```
