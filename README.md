# Python venv and modules demo

This project is based on [good tips how to organise project](https://bulldogjob.pl/readme/dobry-sposob-na-ustrukturyzowanie-projektu-w-pythonie)

# Getting started
```
python3 -m venv venv
source ./venv/bin/activate
pip install -r requirements.txt
pytest
```

# Tips

## Create virtual environment
```
python3 -m venv venv
```

## Activate environment
```
source ./venv/bin/activate
```
## Deactivate environment
```
deactivate
```

## Print all requirements
```
pip freeze
# or put in requirements.txt file
pip freeze > requirements.txt
```

## Install required python packages
```
pip install -r requirements.txt
```

## Run pytests

For `greetings.py` is created `test_greetings.py`. You can run tests with:
```
pytest
```

## How module and python packages works

Modules are located in `./another_directory` and its usage is in `package_module_demo.py`
