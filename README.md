# test-uv

A Python project created with uv.

## Description

*Please provide a detailed description of your project here.*

This project is initialized with a simple `main.py` that prints a greeting. It uses `uv` for package management.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd test-repo
    ```

2.  **Create a virtual environment and install dependencies:**
    This project uses `uv`. You can install the dependencies listed in `pyproject.toml` and `requirements.txt`.
    ```bash
    # It's recommended to use a virtual environment
    python -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`

    # Install dependencies using uv (or pip)
    uv pip install -r requirements.txt
    ```

## Usage

To run the main script:

```bash
python main.py
```

## Dependencies

This project relies on the following main libraries:

*   **langchain**: For building applications with LLMs.
*   **pandas**: For data manipulation and analysis.
*   **python-dotenv**: For managing environment variables.

The specific versions are managed in `pyproject.toml` and `uv.lock`.