# Base setup for python projeckt
Base setup for a python project for vscode
It's tested on a Ubuntu 20.04 computer with python3 and pip3 installed

## This repo includes
### requirements.txt
```
black==21.11b1
flake8==4.0.1
```
### .vscode/
- Settnings to set black to formater and flake8 to linter

### venv/
- A python virtual environment

## How to use
- Create a new folder (linux)
```console
mkdir myfolder
```
- Start a local git repository
- Create a new folder (linux)
```console
git init
```
- Clone into your new folder
```console
git clone https://github.com/johanalmquist/python-projects-template.git
```

- Create a virtual environment (for linux)
```console
python3 -m venv .venv
```

- Activate virtual environment
```console
source .venv/bin/activate
```
- Install pip packages
```console
pip3 install -r requirements.txt
```


