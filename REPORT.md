- uv run uses the Python executable inside .venv.
- sys.prefix points to .venv.
- sys.base_prefix points to the base Python installation.
- When sys.prefix != sys.base_prefix, Python is running in a virtual environment.
- uv run adjusts the execution environment automatically, so manual activation is unnecessary.

