
# Crash Guild API

This project is a case study for Flask, Poetry, SQLAlchemy usage and Python skills refinement. Some tips and hints are **very very** welcomed.


## Installing

To install the project it is needed Poetry to be downloaded. We use it to manager the project's dependencies and their versions.

As we have Poetry installed, we can downloaded the dependencies with the commands.

```bash
  poetry install
```


## Common Errors
- When you tried to install the dependencies, the **venv folder** did not appear in the root? Or you can't select the right interpreter in VSCode?

Try execute the following command:

```bash
  poetry config virtualenvs.in-project true
```

This will be creating the **.venv folder** and VSCode will recognize it automatically.

If you tried something before and Poetry created the folder by default, try this:

```bash
  poetry env list
  poetry env remove <venv-folder-name>
  poetry install # will create a new environment using your updated configuration
```
