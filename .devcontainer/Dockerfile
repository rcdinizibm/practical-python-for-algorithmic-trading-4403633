# Use a Python development container image from VS Code
FROM mcr.microsoft.com/vscode/devcontainers/python:3.10

# Install additional Python utilities
RUN pip install --no-cache-dir autopep8 black flake8 mypy pylint yapf bandit pycodestyle pydocstyle

# Ensure all installed Python utilities are available in the PATH
ENV PATH="/usr/local/bin:$PATH"
