# Mercor-Hackathon

> If you're using this project , **remember to set the OpenAI API key** in `main.py`.

follow the installation instructions to get started.

* 1
```
Fork the repository 
```
* 2
```
Clone the repo
```

* Open the repo in your VS Code

* Make sure to upgrade your Python version to >= 3.8.1 and add it in your path.

* Now, you need to install poetry, which is like a python package manager and it does try to make your life easier. Really tries. Believe me.

**FOR WINDOWS:**

* Download a python version >= 3.8.1: https://www.python.org/downloads/ and make sure you add it to PATH while installing

* Just
```
pip install poetry
``` 

* Ctrl + Shift + P and search for Terminal: Select Default Profile and select Command Prompt

* poetry config virtualenvs.in-project true in the VSCode terminal inside the folder where you have cloned textbase repo to add it in VSCode path (interpreter path)

```
poetry shell 
```

* Ctrl + Shift + P  and go to Python: Select Interpreter  and make sure after running this you have selected the poetry interpreter

```
poetry install .
```
```
poetry run python textbase/textbase_cli.py test main.py .
```
