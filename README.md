# deepagent

A Python project using `uv` for package management.

## Setup

This project uses [uv](https://github.com/astral-sh/uv) for package management and virtual environment management.

### Installation

First, install `uv` if you haven't already:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Then, setup the project:
```bash
uv sync
```

This will create a virtual environment and install all dependencies.

## Running the Project

To run the hello world example:
```bash
uv run python hello.py
```

To run commands in the virtual environment:
```bash
uv run python <script.py>
```

## Adding Dependencies

To add a new dependency:
```bash
uv add <package-name>
```

To add a dev dependency:
```bash
uv add --dev <package-name>
```

## Project Structure

- `deepagent/` - Main package directory
- `hello.py` - Example Hello World script
- `pyproject.toml` - Project configuration and dependencies
- `.python-version` - Python version specification (3.11)
- `uv.lock` - Locked dependencies (auto-generated)
