# Setup

## Install apt dependencies
```
sudo apt install virtualenv
```

## Python virtual environment
`virtualenv` lets you install Python packages without conflictiong with other workspaces

### Create the virtual environment
```
virtualenv -p python3.10 venv
```
### Activate the virtual environment
```
source venv/bin/activate
```
Make sure you activate it each time you use the training code.

## Install other dependencies
```
pip install -r requirements.txt
```

# Use interpreter
```
interpreter -m azure/gpt-4-model
```
Before above, you need to set AZURE_API_KEY
