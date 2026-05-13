# MIT-6.100L — Project virtual environment

Quick setup for an isolated Python environment for this workspace.

Activation (macOS, zsh):

    source .venv/bin/activate

Install packages (while activated):

    pip install <package>
    pip install -r requirements.txt

Save current deps:

    pip freeze > requirements.txt

Deactivate:

    deactivate

In VS Code: open the Command Palette → `Python: Select Interpreter` and choose
the `.venv` interpreter at `.venv/bin/python`.
