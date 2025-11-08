# Project virtual environment

A Python virtual environment is available at `.venv` in the project root.

Activate (macOS / zsh):

    source ".venv/bin/activate"

Upgrade pip and install dependencies:

    python -m pip install --upgrade pip
    pip install -r requirements.txt

Notes:
- The `.venv` directory is local to this project and contains a private Python interpreter and site-packages.
- If you want to recreate the venv instead of copying it (recommended when moving between machines), delete `.venv` then run:

    python3 -m venv ".venv"

Then activate and install the requirements as shown above.
