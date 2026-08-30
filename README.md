# Learning Python

Welcome to the Learning-Python repository — a personal collection of Python exercises, examples, projects, and notes designed to help you build and track your Python learning journey.

## Repository purpose

This repository is intended for:

- Storing short exercises and practice problems
- Collecting example scripts and mini-projects
- Keeping notes, recipes, and tips for Python features and libraries
- Demonstrating learning progress with runnable code and notebooks

## Recommended structure

Organize the repository using the following conventions (adjust to fit your workflow):

- `exercises/` — short practice problems and katas (each in its own folder)
- `projects/` — larger projects or multi-file examples
- `notebooks/` — Jupyter notebooks for experimentation and tutorials
- `examples/` — small, focused example scripts demonstrating a concept
- `scripts/` — utility or helper scripts
- `docs/` — supporting documentation, guides, or cheat sheets

If these directories don't exist yet, create them as you add content.

## Getting started

Prerequisites

- Python 3.8 or newer (3.10+ recommended)
- pip (or use poetry/pipenv if you prefer)

Quick start

1. Clone the repository:

   git clone https://github.com/speedyrain/Learning-Python.git
   cd Learning-Python

2. (Optional) Create and activate a virtual environment:

   python -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   .\.venv\Scripts\activate  # Windows PowerShell

3. Install dependencies (if a requirements file exists):

   pip install -r requirements.txt

4. Run an example script:

   python examples/hello_world.py

5. Open a notebook:

   jupyter notebook notebooks/SomeNotebook.ipynb


## Contributing

Contributions are welcome. A simple workflow:

1. Fork the repo
2. Create a branch named `feature/your-topic` or `exercise/<name>`
3. Add your code, tests, and a short README for the new exercise or project
4. Run any tests or notebooks locally
5. Open a pull request describing what you added and why

Guidelines

- Keep examples small and focused on a single concept
- Prefer clear variable names and short helper functions
- Add comments or short README files for non-trivial exercises

## Code style and testing

- Use black/flake8/isort for consistent formatting
- Add small unit tests under `tests/` for projects that grow beyond a single script

## Examples and learning ideas

- Data structures (lists, dicts, sets, tuples)
- Functional programming (map/filter/reduce, list comprehensions)
- OOP basics (classes, inheritance, dunder methods)
- Working with files and I/O
- Web requests (requests, httpx)
- Data analysis with pandas
- Simple web apps (Flask, FastAPI)
- Automation and scripting

## License

This repository currently does not include a LICENSE file. If you want to publish this work under an open-source license, add a `LICENSE` file (for example, the MIT License) or tell me which license you'd like and I can add one.

## Contact / Author

Maintained by @speedyrain

If you'd like suggestions for what to add next (exercises, projects, or learning paths), tell me what topics you care about and I can propose a plan or starter exercises.
