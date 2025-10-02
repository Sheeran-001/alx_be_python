# Copilot Instructions for AI Coding Agents

## Project Overview
This codebase is a collection of Python scripts for basic backend web development exercises. Each script in `PYTHON_INTRODUCTION/` solves a distinct, self-contained problem, such as arithmetic operations, area calculations, and simple interest computation.

## Directory Structure
- `PYTHON_INTRODUCTION/`: Contains individual Python scripts. Each file is a standalone exercise, not a module or package.
- No external dependencies or package management files (e.g., `requirements.txt`).
- No test suite or build system is present.

## Coding Patterns & Conventions
- Each script is expected to be executable directly (e.g., `python basic_operations.py`).
- Scripts use standard Python syntax and built-in functions only.
- Input/output is typically handled via `input()` and `print()` functions.
- No shared code or cross-file imports; each file is independent.
- Variable and function names are descriptive and match the problem domain (e.g., `future_age_calculator.py` calculates future age).

## Developer Workflows
- **Run scripts:** Use `python <scriptname>.py` from the `PYTHON_INTRODUCTION/` directory.
- **Debugging:** Directly edit and re-run scripts; no advanced debugging or logging is set up.
- **No automated tests:** Manual verification only.

## Examples
- `rectangle_area.py`: Calculates the area of a rectangle from user input.
- `simple_interest.py`: Computes simple interest based on principal, rate, and time.

## Guidance for AI Agents
- Focus on clarity and correctness in each script; avoid unnecessary abstraction.
- When adding new scripts, follow the naming and structure conventions in `PYTHON_INTRODUCTION/`.
- Do not introduce external dependencies or complex project structures unless explicitly requested.
- If refactoring, keep scripts independent unless a new shared module is requested.

## Key Files
- All work is in `PYTHON_INTRODUCTION/`. Each `.py` file is a separate exercise.

---
For questions or unclear conventions, ask the user for clarification before making structural changes.
