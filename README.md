## THIS PROJECT IS ARCHIVED 

Intel will not provide or guarantee development of or support for this project, including but not limited to, maintenance, bug fixes, new releases or updates. 

Patches to this project are no longer accepted by Intel.   

This project has been identified as having known security issues. 

Contact: webadmin@linux.intel.com
# Misinformation Guard

open-source LLM models to be published on behalf of Intel on Hugging Face

## Quickstart

Install `uv` or your package manager of choice. We'll be using `uv`, [an extremely fast Python package and project manager, written in Rust](https://github.com/astral-sh/uv).

Check the `uv` [installation guide for macOS, Linux, and Windows](https://docs.astral.sh/uv/getting-started/installation/)

Create a virtual environment:

```
uv venv venv
```

Activate the virtual environment:

```
source venv/bin/activate
```

Install the pre-commit hooks for formatting code:

```
pre-commit install
```

Install packages to the `.venv`:

```
uv pip install -r requirements.txt
```

Install the package in "editable" mode, which means changes to the Python files will be immediately available without needing to reinstall the package.

```
uv pip install -e .
```
