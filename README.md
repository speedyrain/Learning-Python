# Learning Python

Welcome to the Learning-Python repository — a personal collection of Python exercises, examples, projects, and notes designed to help you learn and track your progress with Python.

## Repository purpose

This repository is intended for:

- Storing short exercises and practice problems
- Collecting example scripts and mini-projects
- Keeping notes, recipes, and tips for Python features and libraries
- Demonstrating learning progress with runnable code and notebooks

## Recommended structure

Organize the repository using these conventions (adapt as needed):

- `exercises/` — short practice problems and katas (each in its own folder)
- `projects/` — larger projects or multi-file examples
- `notebooks/` — Jupyter notebooks for experimentation and tutorials
- `examples/` — small, focused example scripts demonstrating a concept
- `scripts/` — utility or helper scripts
- `tests/` — unit tests for projects that need them
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
   .\.venv\Scripts\activate    # Windows PowerShell

3. Install dependencies (if a requirements file exists):

   pip install -r requirements.txt

4. Run an example script:

   python examples/hello_world.py

5. Open a notebook:

   jupyter notebook notebooks/SomeNotebook.ipynb

## How to add content

- For a new exercise: create `exercises/<exercise-name>/` and include the exercise code, a short README, and any tests.
- For a new project: create `projects/<project-name>/` with a top-level README explaining goals and how to run it.
- For experiments: put exploratory code and analysis in `notebooks/` and keep notebooks descriptive.

## Contributing

Contributions are welcome. A simple workflow:

1. Fork the repo
2. Create a branch named `feature/<topic>` or `exercise/<name>`
3. Add your code, tests, and a short README for the new exercise or project
4. Run any tests or notebooks locally
5. Open a pull request describing what you added and why

Guidelines

- Keep examples small and focused on a single concept
- Use clear variable names and small helper functions
- Add comments and a short README for non-trivial exercises
- Include tests for logic that should be validated

## Code style and testing

- Use tools like black, flake8, and isort for consistent formatting
- Add small unit tests under `tests/` for projects that grow beyond a single script
- Consider CI (GitHub Actions) to run tests on pull requests

## Learning ideas and examples

- Data structures: lists, dicts, sets, tuples
- Functional tools: list comprehensions, map/filter/reduce
- OOP basics: classes, inheritance, dunder methods
- File I/O and serialization (JSON, CSV)
- Web requests and APIs (requests, httpx)
- Data analysis with pandas and matplotlib
- Web apps: Flask or FastAPI simple examples
- Automation and scripting for real-world tasks

## License

This repository does not include a LICENSE file yet. If you want to publish under an open-source license, add a `LICENSE` file (for example, MIT) or tell me which license you'd like and I can add one.

## Contact / Maintainer

Maintained by @speedyrain

If you'd like suggestions for exercises, projects, or a learning plan, tell me which topics interest you and I can propose a roadmap and starter exercises.
